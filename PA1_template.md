# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data
getwd()
activityData <- read.csv(unz("activity.zip", "activity.csv"))
#Ignore NAs
clean_activityData <- na.omit(activityData)

## What is mean total number of steps taken per day?
library(data.table)
dt <- data.table(clean_activityData)

df <- as.data.frame(dt[,list(total = sum(steps)), by =c("date")])
hist(df$total, col=3, main="Histogram of the total number of steps per day", 
     xlab="Total number of steps per day", border = 3)
     ## What is the average daily activity pattern?
mean1 <- mean(df$total)
median1 <- median(df$total)


interval_steps1 <- aggregate(steps ~ interval, clean_activityData, mean)

plot(interval_steps1$interval, interval_steps1$steps, type='l', col=1, 
     main="Average number of steps averaged across all days", xlab="Interval", 
     ylab="Average number of steps")
     
max_row_id <- which.max(interval_steps1$steps)    
interval_steps1 [max_row_id, ]    
## Inputing missing values
data_NA <- activityData[!complete.cases(activityData),]
Total_rows <- nrow(data_NA)


##
for (i in 1:nrow(df)){
  if (is.na(activityData$steps[i])){
    interval_val <- activityData$interval[i]
    row_id <- which(interval_steps1$interval == interval_val)
    steps_val <- interval_steps1$steps[row_id]
    activityData$steps[i] <- steps_val
  }
}

## 4
# aggregate steps as per date to get total number of steps in a day
inserted <- aggregate(steps ~ date, activityData, sum)

# create histogram of total number of steps in a day
hist(inserted$steps, col=3, border = 3, main="(Imputed) Histogram of total number of steps per day", xlab="Total number of steps in a day")
mean2 <- mean(inserted$steps)
median2 <- median(inserted$steps)


## Are there differences in activity patterns between weekdays and weekends?
# Create a new factor variable in the dataset with two levels - "weekday" and "weekend" indicating whether a given date is a weekday or weekend day

day <- weekdays(as.Date(activityData$date))
daylevel <- vector()
for (i in 1:nrow(activityData)) {
    if (day[i] == "Saturday") {
        daylevel[i] <- "Weekend"
    } else if (day[i] == "Sunday") {
        daylevel[i] <- "Weekend"
    } else {
        daylevel[i] <- "Weekday"
    }
}
activityData$daylevel <- daylevel
activityData$daylevel <- factor(activityData$daylevel)

stepsByDay <- aggregate(steps ~ interval + daylevel, data = activityData, mean)
names(stepsByDay) <- c("interval", "daylevel", "steps")

# make the panel plot for weekdays and weekends
library(lattice)

# create the panel plot
xyplot(steps ~ interval | daylevel, stepsByDay, type = "l", layout = c(1, 2), 
    xlab = "Interval", ylab = "Number of steps")

