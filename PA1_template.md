



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>RepData_PeerAssessment1/PA1_template.md at master · SunSmiles13/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="SunSmiles13/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars3.githubusercontent.com/u/14201355?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars3.githubusercontent.com/u/14201355?v=3&amp;s=400" property="og:image" /><meta content="SunSmiles13/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/SunSmiles13/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTQyMDEzNTU6YWFiODVlNDBmOTM2MmI0N2UwMzIzYjg3NWM1ZmFmZGE6NzBlYTQwNzE5MTM0Zjk2MjM0YjAxYTVkNDhjNjEyNjY1OGQ0ODQ4ZTQ4MjY3ZTU0NjI5YTQxODNkNzkzNTY2ZQ==--08b068b56810856ea6cdda65623c8c5a8aec62fa">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="44645F85:448A:1CFC47BC:56770B24" name="octolytics-dimension-request_id" /><meta content="14201355" name="octolytics-actor-id" /><meta content="SunSmiles13" name="octolytics-actor-login" /><meta content="efe459f0d71b7cb3409f3287bc2172bb091177b917c27b13f3eb4a5048f46136" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />
<meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />


  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="SunSmiles13">

        <meta name="expected-hostname" content="github.com">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="2e67a7fd337353c593f4f94830b003ec34551b0b" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-9b9bb5f0e51c6691245fd21719e65aee31f1f33ce4fd41c446dddc1ceb37cbad.css" integrity="sha256-m5u18OUcZpEkX9IXGeZa7jHx8zzk/UHERt3cHOs3y60=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-327ccd956b7110b749a5feef7e1110bd8a7f0074044affc068d39ff982377ae0.css" integrity="sha256-MnzNlWtxELdJpf7vfhEQvYp/AHQESv/AaNOf+YI3euA=" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="ac089033e2e3b15782c37f0126e2b632">

      
  <meta name="description" content="RepData_PeerAssessment1 - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/SunSmiles13/RepData_PeerAssessment1 git https://github.com/SunSmiles13/RepData_PeerAssessment1.git">

  <meta content="14201355" name="octolytics-dimension-user_id" /><meta content="SunSmiles13" name="octolytics-dimension-user_login" /><meta content="48181061" name="octolytics-dimension-repository_id" /><meta content="SunSmiles13/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/SunSmiles13/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github "></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/SunSmiles13/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:SunSmiles13"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell "></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="SunSmiles13/RepData_PeerAssessment1">This repository</span>
  </div>
    <a class="dropdown-item" href="/SunSmiles13/RepData_PeerAssessment1/settings/collaboration" data-ga-click="Header, create new collaborator">
      New collaborator
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/SunSmiles13"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@SunSmiles13" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/14201355?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">SunSmiles13</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/SunSmiles13" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="32OwyIIm54w3o0Pyf7Y8TqStcR/St2EVfARKU/TDhViGLWqwx+LOujEBWVfXn3LIvO9gFMz6TnHu2c+135f5cQ==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div id="js-repo-pjax-container" class="context-loader-container js-repo-nav-next" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="ExaENiOS3k8jOHqTMjPh/d1nn+1wWI9zDlAYm2KxvqtxpRLOJD13HjRTIMG7O7c4DWAnKT8Ocv2ATCvOQhGIcA==" /></div>      <input id="repository_id" name="repository_id" type="hidden" value="48181061" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/SunSmiles13/RepData_PeerAssessment1/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <span class="octicon octicon-eye "></span>
              Unwatch
            </span>
          </a>
          <a class="social-count js-social-count" href="/SunSmiles13/RepData_PeerAssessment1/watchers">
            1
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
              <span class="select-menu-title">Notifications</span>
            </div>

              <div class="select-menu-list js-navigation-container" role="menu">

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <span class="select-menu-item-icon octicon octicon-check"></span>
                  <div class="select-menu-item-text">
                    <input id="do_included" name="do" type="radio" value="included" />
                    <span class="select-menu-item-heading">Not watching</span>
                    <span class="description">Be notified when participating or @mentioned.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span class="octicon octicon-eye"></span>
                      Watch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                  <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                  <div class="select-menu-item-text">
                    <input checked="checked" id="do_subscribed" name="do" type="radio" value="subscribed" />
                    <span class="select-menu-item-heading">Watching</span>
                    <span class="description">Be notified of all conversations.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span class="octicon octicon-eye"></span>
                      Unwatch
                    </span>
                  </div>
                </div>

                <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                  <span class="select-menu-item-icon octicon octicon-check"></span>
                  <div class="select-menu-item-text">
                    <input id="do_ignore" name="do" type="radio" value="ignore" />
                    <span class="select-menu-item-heading">Ignoring</span>
                    <span class="description">Never be notified.</span>
                    <span class="js-select-button-text hidden-select-button-text">
                      <span class="octicon octicon-mute"></span>
                      Stop ignoring
                    </span>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="GBCgiw+Hsna4+hj1HFQrzDyX+WvBjSXVglIGCxxt4IicT8QaKDc8LanUJDIpqrhN6mN9A0VL2yGj6ZlYqCULpw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar SunSmiles13/RepData_PeerAssessment1"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star "></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/SunSmiles13/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="fkhRTotPHx8pqkf0JAtVpyrTlm9vl8EL7w/IL8iEAwTFxGAE9eYy3fsP2L417rIQEBfN2f4xExPrXnUCmwe6SQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star SunSmiles13/RepData_PeerAssessment1"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star "></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/SunSmiles13/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of SunSmiles13/RepData_PeerAssessment1 to your account"
              aria-label="Fork your own copy of SunSmiles13/RepData_PeerAssessment1 to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
              <span class="octicon octicon-repo-forked "></span>
            Fork
          </a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header" data-facebox-id="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/SunSmiles13/RepData_PeerAssessment1/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>

    <a href="/SunSmiles13/RepData_PeerAssessment1/network" class="social-count">
      20,833
    </a>
  </li>
</ul>

    <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="octicon octicon-repo-forked "></span>
  <span class="author"><a href="/SunSmiles13" class="url fn" itemprop="url" rel="author"><span itemprop="title">SunSmiles13</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/SunSmiles13/RepData_PeerAssessment1" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

    <span class="fork-flag">
      <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
    </span>
</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <a href="/SunSmiles13/RepData_PeerAssessment1" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /SunSmiles13/RepData_PeerAssessment1">
    <span class="octicon octicon-code "></span>
    Code
</a>

  <a href="/SunSmiles13/RepData_PeerAssessment1/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /SunSmiles13/RepData_PeerAssessment1/pulls">
    <span class="octicon octicon-git-pull-request "></span>
    Pull requests
    <span class="counter">0</span>
</a>
    <a href="/SunSmiles13/RepData_PeerAssessment1/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /SunSmiles13/RepData_PeerAssessment1/wiki">
      <span class="octicon octicon-book "></span>
      Wiki
</a>
  <a href="/SunSmiles13/RepData_PeerAssessment1/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /SunSmiles13/RepData_PeerAssessment1/pulse">
    <span class="octicon octicon-pulse "></span>
    Pulse
</a>
  <a href="/SunSmiles13/RepData_PeerAssessment1/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /SunSmiles13/RepData_PeerAssessment1/graphs">
    <span class="octicon octicon-graph "></span>
    Graphs
</a>
    <a href="/SunSmiles13/RepData_PeerAssessment1/settings" class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks /SunSmiles13/RepData_PeerAssessment1/settings">
      <span class="octicon octicon-gear "></span>
      Settings
</a>
</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/SunSmiles13/RepData_PeerAssessment1/blob/a8ff07669c923c0923558b322df666d2fe9e3960/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:bc740e448cd6bd5911ebcfe2790f4708 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Find or create a branch…" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Find or create a branch…">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Find or create a branch…" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/SunSmiles13/RepData_PeerAssessment1/blob/master/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/branches" class="js-create-branch select-menu-item select-menu-new-item-form js-navigation-item js-new-item-form" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="J9lAQ0LkTDzp/+qMqqsGvsdAKIXg3o3p0bzEF3J+2BsomFMP474OqP1lERmaNDKw+rVSN/T3wXvmZV2/X0ZEtg==" /></div>
            <span class="octicon octicon-git-branch select-menu-item-icon"></span>
            <div class="select-menu-item-text">
              <span class="select-menu-item-heading">Create branch: <span class="js-new-item-name"></span></span>
              <span class="description">from ‘master’</span>
            </div>
            <input type="hidden" name="name" id="name" class="js-new-item-value">
            <input type="hidden" name="branch" id="branch" value="master">
            <input type="hidden" name="path" id="path" value="PA1_template.md">
</form>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/SunSmiles13/RepData_PeerAssessment1/find/master"
          class="js-show-file-finder btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/SunSmiles13/RepData_PeerAssessment1" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/SunSmiles13/RepData_PeerAssessment1/commit/af2d0e6ae5402a2183713784796c5e7c44f184ec" data-pjax>
          af2d0e6
        </a>
        <time datetime="2015-12-20T17:59:13Z" is="relative-time">Dec 20, 2015</time>
      </span>
      <div>
        <img alt="@SunSmiles13" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/14201355?v=3&amp;s=40" width="20" />
        <a href="/SunSmiles13" class="user-mention" rel="author">SunSmiles13</a>
          <a href="/SunSmiles13/RepData_PeerAssessment1/commit/af2d0e6ae5402a2183713784796c5e7c44f184ec" class="message" data-pjax="true" title="First commit">First commit</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>1</strong>
         contributor
      </a>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@SunSmiles13" height="24" src="https://avatars2.githubusercontent.com/u/14201355?v=3&amp;s=48" width="24" />
            <a href="/SunSmiles13">SunSmiles13</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/SunSmiles13/RepData_PeerAssessment1/raw/master/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/SunSmiles13/RepData_PeerAssessment1/blame/master/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/SunSmiles13/RepData_PeerAssessment1/commits/master/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/edit/master/PA1_template.md" class="inline-form js-update-url-with-hash" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="EiVIbYZKVe1FPW4T7qbwIIYJZ78oIL/NBPRF7OFj5OVJ3GW5CCn9ivkl4QHsLAIvXUaF9/niRuPB2Cm6xWA29g==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Edit this file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil"></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/SunSmiles13/RepData_PeerAssessment1/delete/master/PA1_template.md" class="inline-form" data-form-nonce="2e67a7fd337353c593f4f94830b003ec34551b0b" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="3Hogm9VC3qII6R2HJzxTTHXAGxSS09/TtmA2yBYBdsB6kyC+CtrjE4FqLB9ALQKkZ8Mm0br1Pi4d2SeRIvRMdA==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Delete this file" data-disable-with>
            <span class="octicon octicon-trashcan"></span>
          </button>
</form>  </div>

  <div class="file-info">
      82 lines (62 sloc)
      <span class="file-info-divider"></span>
    2.64 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research: Peer Assessment 1</h1>

<h2><a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<p>getwd()
activityData &lt;- read.csv(unz("activity.zip", "activity.csv"))</p>

<h1><a id="user-content-ignore-nas" class="anchor" href="#ignore-nas" aria-hidden="true"><span class="octicon octicon-link"></span></a>Ignore NAs</h1>

<p>clean_activityData &lt;- na.omit(activityData)</p>

<h2><a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<p>library(data.table)
dt &lt;- data.table(clean_activityData)</p>

<p>df &lt;- as.data.frame(dt[,list(total = sum(steps)), by =c("date")])
hist(df$total, col=3, main="Histogram of the total number of steps per day", 
     xlab="Total number of steps per day", border = 3)
     ## What is the average daily activity pattern?
mean1 &lt;- mean(df$total)
median1 &lt;- median(df$total)</p>

<p>interval_steps1 &lt;- aggregate(steps ~ interval, clean_activityData, mean)</p>

<p>plot(interval_steps1$interval, interval_steps1$steps, type='l', col=1, 
     main="Average number of steps averaged across all days", xlab="Interval", 
     ylab="Average number of steps")</p>

<p>max_row_id &lt;- which.max(interval_steps1$steps)<br>
interval_steps1 [max_row_id, ]    </p>

<h2><a id="user-content-inputing-missing-values" class="anchor" href="#inputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Inputing missing values</h2>

<p>data_NA &lt;- activityData[!complete.cases(activityData),]
Total_rows &lt;- nrow(data_NA)</p>

<p>for (i in 1:nrow(df)){
  if (is.na(activityData$steps[i])){
    interval_val &lt;- activityData$interval[i]
    row_id &lt;- which(interval_steps1$interval == interval_val)
    steps_val &lt;- interval_steps1$steps[row_id]
    activityData$steps[i] &lt;- steps_val
  }
}</p>

<h2><a id="user-content-4" class="anchor" href="#4" aria-hidden="true"><span class="octicon octicon-link"></span></a>4</h2>

<h1><a id="user-content-aggregate-steps-as-per-date-to-get-total-number-of-steps-in-a-day" class="anchor" href="#aggregate-steps-as-per-date-to-get-total-number-of-steps-in-a-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>aggregate steps as per date to get total number of steps in a day</h1>

<p>inserted &lt;- aggregate(steps ~ date, activityData, sum)</p>

<h1><a id="user-content-create-histogram-of-total-number-of-steps-in-a-day" class="anchor" href="#create-histogram-of-total-number-of-steps-in-a-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>create histogram of total number of steps in a day</h1>

<p>hist(inserted$steps, col=3, border = 3, main="(Imputed) Histogram of total number of steps per day", xlab="Total number of steps in a day")
mean2 &lt;- mean(inserted$steps)
median2 &lt;- median(inserted$steps)</p>

<h2><a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<h1><a id="user-content-create-a-new-factor-variable-in-the-dataset-with-two-levels---weekday-and-weekend-indicating-whether-a-given-date-is-a-weekday-or-weekend-day" class="anchor" href="#create-a-new-factor-variable-in-the-dataset-with-two-levels---weekday-and-weekend-indicating-whether-a-given-date-is-a-weekday-or-weekend-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>Create a new factor variable in the dataset with two levels - "weekday" and "weekend" indicating whether a given date is a weekday or weekend day</h1>

<p>day &lt;- weekdays(as.Date(activityData$date))
daylevel &lt;- vector()
for (i in 1:nrow(activityData)) {
    if (day[i] == "Saturday") {
        daylevel[i] &lt;- "Weekend"
    } else if (day[i] == "Sunday") {
        daylevel[i] &lt;- "Weekend"
    } else {
        daylevel[i] &lt;- "Weekday"
    }
}
activityData$daylevel &lt;- daylevel
activityData$daylevel &lt;- factor(activityData$daylevel)</p>

<p>stepsByDay &lt;- aggregate(steps ~ interval + daylevel, data = activityData, mean)
names(stepsByDay) &lt;- c("interval", "daylevel", "steps")</p>

<h1><a id="user-content-make-the-panel-plot-for-weekdays-and-weekends" class="anchor" href="#make-the-panel-plot-for-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>make the panel plot for weekdays and weekends</h1>

<p>library(lattice)</p>

<h1><a id="user-content-create-the-panel-plot" class="anchor" href="#create-the-panel-plot" aria-hidden="true"><span class="octicon octicon-link"></span></a>create the panel plot</h1>

<p>xyplot(steps ~ interval | daylevel, stepsByDay, type = "l", layout = c(1, 2), 
    xlab = "Interval", ylab = "Number of steps")</p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>

    </div>
  </div>

    </div>

        <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github " title="GitHub "></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.08125s from github-fe129-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" integrity="sha256-7460qJ7p88i3YTMH/liaj1cFgX987ie+xRzl6WMjSr8=" src="https://assets-cdn.github.com/assets/frameworks-ef8eb4a89ee9f3c8b7613307fe589a8f5705817f7cee27bec51ce5e963234abf.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-S2uOfRHrt7zoUSbTtBMMgAQfKubV1u+JAajAw/fLgNI=" src="https://assets-cdn.github.com/assets/github-4b6b8e7d11ebb7bce85126d3b4130c80041f2ae6d5d6ef8901a8c0c3f7cb80d2.js"></script>
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

