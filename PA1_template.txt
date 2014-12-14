



<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>RepData_PeerAssessment1/PA1_template.md at master · zacks1/RepData_PeerAssessment1</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="zacks1/RepData_PeerAssessment1" name="twitter:title" /><meta content="RepData_PeerAssessment1" name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/7551682?v=3&amp;s=400" name="twitter:image:src" />
<meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/7551682?v=3&amp;s=400" property="og:image" /><meta content="zacks1/RepData_PeerAssessment1" property="og:title" /><meta content="https://github.com/zacks1/RepData_PeerAssessment1" property="og:url" /><meta content="RepData_PeerAssessment1" property="og:description" />

      <meta name="browser-stats-url" content="/_stats">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035">
    <link rel="xhr-socket" href="/_sockets">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="6F5DE3DA:6263:113754E:548E098C" name="octolytics-dimension-request_id" /><meta content="8358476" name="octolytics-actor-id" /><meta content="utkarshjain2608" name="octolytics-actor-login" /><meta content="11f777547ca193e52c092f70a5c07b2623f1b54af629eed06e17a1d3524680ec" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />

    
    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="WEYpkh+Pv1Rp90IO9d+T+29uS6R5mNF4vZLJQV2xY/hnVyJ+7pmWnF+d9lgNRmlQMt2uP9B8bXobKT+0NsfSXg==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-c7f434a471766a748d862b4cb294526acd6901321d901cc64028f53af8490603.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://assets-cdn.github.com/assets/github2-761398b51b4a87682bde8f8b3479da06f8bde788a3fae6fb10b018a384748cf0.css" media="all" rel="stylesheet" type="text/css" />
    
    


    <meta http-equiv="x-pjax-version" content="52744ce9703c979de4f8f2f444b85ff4">

      
  <meta name="description" content="RepData_PeerAssessment1">
  <meta name="go-import" content="github.com/zacks1/RepData_PeerAssessment1 git https://github.com/zacks1/RepData_PeerAssessment1.git">

  <meta content="7551682" name="octolytics-dimension-user_id" /><meta content="zacks1" name="octolytics-dimension-user_login" /><meta content="19913952" name="octolytics-dimension-repository_id" /><meta content="zacks1/RepData_PeerAssessment1" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="19913952" name="octolytics-dimension-repository_network_root_id" /><meta content="zacks1/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/zacks1/RepData_PeerAssessment1/commits/master.atom" rel="alternate" title="Recent Commits to RepData_PeerAssessment1:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      
      


      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" ga-data-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/zacks1/RepData_PeerAssessment1/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/zacks1/RepData_PeerAssessment1/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>
      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item explore">
          <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
          </li>
        <li class="header-nav-item">
          <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
        </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/utkarshjain2608" data-ga-click="Header, go to profile, text:username">
      <img alt="utkarshjain2608" class="avatar" data-user="8358476" height="20" src="https://avatars2.githubusercontent.com/u/8358476?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">utkarshjain2608</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="#" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      
<ul class="dropdown-menu">
  <li>
    <a href="/new"><span class="octicon octicon-repo"></span> New repository</a>
  </li>
  <li>
    <a href="/organizations/new"><span class="octicon octicon-organization"></span> New organization</a>
  </li>


    <li class="dropdown-divider"></li>
    <li class="dropdown-header">
      <span title="zacks1/RepData_PeerAssessment1">This repository</span>
    </li>
      <li>
        <a href="/zacks1/RepData_PeerAssessment1/issues/new"><span class="octicon octicon-issue-opened"></span> New issue</a>
      </li>
</ul>

    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="utqRL8kwKdeSxXt2GgyVMxWdIM351ZLQejBdBG9Dl2RZn9YfvVKyEftTxVDavTCnYaU5neA7r7absXW27/hIKQ==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>


    
  </div>
</div>

      

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

    <li class="subscription">
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="a4uzXhwUpjVECTFeeZ2hL8XmgNvuA/5K+Z5iwoZ6KvcKn27CMMA7yfQOA4LRvwegFNUqG3wHZ7Qy4+eDnV8aZw==" /></div>  <input id="repository_id" name="repository_id" type="hidden" value="19913952" />

    <div class="select-menu js-menu-container js-select-menu">
      <a class="social-count js-social-count" href="/zacks1/RepData_PeerAssessment1/watchers">
        1
      </a>
      <a href="/zacks1/RepData_PeerAssessment1/subscription"
        class="minibutton select-menu-button with-count js-menu-target" role="button" tabindex="0" aria-haspopup="true">
        <span class="js-select-button">
          <span class="octicon octicon-eye"></span>
          Watch
        </span>
      </a>

      <div class="select-menu-modal-holder">
        <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
            <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
          </div> <!-- /.select-menu-header -->

          <div class="select-menu-list js-navigation-container" role="menu">

            <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                <h4>Not watching</h4>
                <span class="description">Be notified when participating or @mentioned.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Watch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                <h4>Watching</h4>
                <span class="description">Be notified of all conversations.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-eye"></span>
                  Unwatch
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

            <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <div class="select-menu-item-text">
                <input id="do_ignore" name="do" type="radio" value="ignore" />
                <h4>Ignoring</h4>
                <span class="description">Never be notified.</span>
                <span class="js-select-button-text hidden-select-button-text">
                  <span class="octicon octicon-mute"></span>
                  Stop ignoring
                </span>
              </div>
            </div> <!-- /.select-menu-item -->

          </div> <!-- /.select-menu-list -->

        </div> <!-- /.select-menu-modal -->
      </div> <!-- /.select-menu-modal-holder -->
    </div> <!-- /.select-menu -->

</form>
    </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/zacks1/RepData_PeerAssessment1/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="YEAqvlSSs0P4ozVkdxi+wvHsAS8iyUykmlJ6cgZ07Hl5RdqWiWdUgNHMHUWMMN5ovnjVa7jQm6Tty6ea8QiMfA==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Unstar this repository" title="Unstar zacks1/RepData_PeerAssessment1">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/zacks1/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>
    <form accept-charset="UTF-8" action="/zacks1/RepData_PeerAssessment1/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="JKSRkSU7bzVrFyeso6D0Zu/fcOTLWFWO/6ki8d3WwGwtEsrsmS1Zr9U01a0BGg5zKc5bgJlIVMX0tWCryDGEJw==" /></div>
      <button
        class="minibutton with-count js-toggler-target star-button"
        aria-label="Star this repository" title="Star zacks1/RepData_PeerAssessment1">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/zacks1/RepData_PeerAssessment1/stargazers">
          0
        </a>
</form>  </div>

  </li>


        <li>
          <a href="/zacks1/RepData_PeerAssessment1/fork" class="minibutton with-count js-toggler-target fork-button tooltipped-n" title="Fork your own copy of zacks1/RepData_PeerAssessment1 to your account" aria-label="Fork your own copy of zacks1/RepData_PeerAssessment1 to your account" rel="nofollow" data-method="post">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/zacks1/RepData_PeerAssessment1/network" class="social-count">3</a>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/zacks1" class="url fn" itemprop="url" rel="author"><span itemprop="title">zacks1</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/zacks1/RepData_PeerAssessment1" class="js-current-repository" data-pjax="#js-repo-pjax-container">RepData_PeerAssessment1</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/zacks1/RepData_PeerAssessment1/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/zacks1/RepData_PeerAssessment1" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /zacks1/RepData_PeerAssessment1">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/zacks1/RepData_PeerAssessment1/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /zacks1/RepData_PeerAssessment1/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull Requests">
      <a href="/zacks1/RepData_PeerAssessment1/pulls" aria-label="Pull Requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /zacks1/RepData_PeerAssessment1/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull Requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>


      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/zacks1/RepData_PeerAssessment1/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /zacks1/RepData_PeerAssessment1/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/zacks1/RepData_PeerAssessment1/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /zacks1/RepData_PeerAssessment1/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/zacks1/RepData_PeerAssessment1/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /zacks1/RepData_PeerAssessment1/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                
  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/zacks1/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:zacks1/RepData_PeerAssessment1.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/zacks1/RepData_PeerAssessment1" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="github-windows://openRepo/https://github.com/zacks1/RepData_PeerAssessment1" class="minibutton sidebar-button" title="Save zacks1/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop." aria-label="Save zacks1/RepData_PeerAssessment1 to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>

                <a href="/zacks1/RepData_PeerAssessment1/archive/master.zip"
                   class="minibutton sidebar-button"
                   aria-label="Download the contents of zacks1/RepData_PeerAssessment1 as a zip file"
                   title="Download the contents of zacks1/RepData_PeerAssessment1 as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/zacks1/RepData_PeerAssessment1/blob/b22934bf3df59417e45152fa6c90c22fbfb58ce7/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:ace2f5718fae72f92e6f2a8ca58ac5af -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="minibutton select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div> <!-- /.select-menu-header -->

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div><!-- /.select-menu-tabs -->
      </div><!-- /.select-menu-filters -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item selected">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/zacks1/RepData_PeerAssessment1/blob/master/PA1_template.md"
                 data-name="master"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="master">master</a>
            </div> <!-- /.select-menu-item -->
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div> <!-- /.select-menu-list -->

    </div> <!-- /.select-menu-modal -->
  </div> <!-- /.select-menu-modal-holder -->
</div> <!-- /.select-menu -->

  <div class="button-group right">
    <a href="/zacks1/RepData_PeerAssessment1/find/master"
          class="js-show-file-finder minibutton empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard minibutton zeroclipboard-button" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/zacks1/RepData_PeerAssessment1" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">RepData_PeerAssessment1</span></a></span></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="zacks1" class="avatar" data-user="7551682" height="24" src="https://avatars3.githubusercontent.com/u/7551682?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/zacks1" rel="author">zacks1</a></span>
        <time datetime="2014-05-18T15:44:44Z" is="relative-time">May 18, 2014</time>
        <div class="commit-title">
            <a href="/zacks1/RepData_PeerAssessment1/commit/b22934bf3df59417e45152fa6c90c22fbfb58ce7" class="message" data-pjax="true" title="commit2">commit2</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="zacks1" data-user="7551682" height="24" src="https://avatars3.githubusercontent.com/u/7551682?v=3&amp;s=48" width="24" />
            <a href="/zacks1">zacks1</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file-box">
  <div class="file">
    <div class="meta clearfix">
      <div class="info file-name">
          <span>145 lines (105 sloc)</span>
          <span class="meta-divider"></span>
        <span>2.859 kb</span>
      </div>
      <div class="actions">
        <div class="button-group">
          <a href="/zacks1/RepData_PeerAssessment1/raw/master/PA1_template.md" class="minibutton " id="raw-url">Raw</a>
            <a href="/zacks1/RepData_PeerAssessment1/blame/master/PA1_template.md" class="minibutton js-update-url-with-hash">Blame</a>
          <a href="/zacks1/RepData_PeerAssessment1/commits/master/PA1_template.md" class="minibutton " rel="nofollow">History</a>
        </div><!-- /.button-group -->

          <a class="octicon-button tooltipped tooltipped-nw"
             href="github-windows://openRepo/https://github.com/zacks1/RepData_PeerAssessment1?branch=master&amp;filepath=PA1_template.md" aria-label="Open this file in GitHub for Windows">
              <span class="octicon octicon-device-desktop"></span>
          </a>

              <a class="octicon-button tooltipped tooltipped-n js-update-url-with-hash"
                 aria-label="Clicking this button will fork this project so you can edit the file"
                 href="/zacks1/RepData_PeerAssessment1/edit/master/PA1_template.md"
                 data-method="post" rel="nofollow"><span class="octicon octicon-pencil"></span></a>

            <a class="octicon-button danger tooltipped tooltipped-s"
               href="/zacks1/RepData_PeerAssessment1/delete/master/PA1_template.md"
               aria-label="Fork this project and delete file"
               data-method="post" data-test-id="delete-blob-file" rel="nofollow">
          <span class="octicon octicon-trashcan"></span>
        </a>
      </div><!-- /.actions -->
    </div>
    
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research: Peer Assessment 1</h1>

<h2>
<a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-r"><pre><span class="pl-vo">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s1"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)
<span class="pl-vo">data_waNA</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">data</span>[which(<span class="pl-vo">data</span><span class="pl-k">$</span><span class="pl-vo">steps</span> <span class="pl-k">!=</span> <span class="pl-s1"><span class="pl-pds">"</span>NA<span class="pl-pds">"</span></span>), ]</pre></div>

<h2>
<a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<div class="highlight highlight-r"><pre>library(<span class="pl-vo">plyr</span>)</pre></div>

<pre><code>## Warning: package 'plyr' was built under R version 3.0.3
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-vo">daily_steps</span> <span class="pl-k">&lt;-</span> ddply(<span class="pl-vo">data_waNA</span>, .(<span class="pl-vo">date</span>), <span class="pl-vo">summarise</span>, <span class="pl-v">steps</span> <span class="pl-k">=</span> sum(<span class="pl-vo">steps</span>))
hist(<span class="pl-vo">daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>steps per day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/zacks1/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-2.png" target="_blank"><img src="/zacks1/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-2.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre>
<span class="pl-c"># mean and median total number of steps taken per day</span>

mean(<span class="pl-vo">daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-r"><pre>median(<span class="pl-vo">daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)</pre></div>

<pre><code>## [1] 10765
</code></pre>

<h2>
<a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-r"><pre><span class="pl-vo">average_date</span> <span class="pl-k">&lt;-</span> ddply(<span class="pl-vo">data_waNA</span>, .(<span class="pl-vo">interval</span>), <span class="pl-vo">summarise</span>, <span class="pl-v">steps</span> <span class="pl-k">=</span> mean(<span class="pl-vo">steps</span>))
plot(<span class="pl-vo">average_date</span><span class="pl-k">$</span><span class="pl-vo">interval</span>, <span class="pl-vo">average_date</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>, 
    <span class="pl-v">ylab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average steps<span class="pl-pds">"</span></span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Average daily activity<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/zacks1/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-3.png" target="_blank"><img src="/zacks1/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-3.png" alt="plot of chunk unnamed-chunk-3" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre>
<span class="pl-c"># Which 5-minute interval, on average across all the days in the dataset,</span>
<span class="pl-c"># contains the maximum number of steps?</span>
<span class="pl-vo">average_date</span>[<span class="pl-vo">average_date</span><span class="pl-k">$</span><span class="pl-vo">steps</span> <span class="pl-k">==</span> max(<span class="pl-vo">average_date</span><span class="pl-k">$</span><span class="pl-vo">steps</span>), ]</pre></div>

<pre><code>##     interval steps
## 104      835 206.2
</code></pre>

<div class="highlight highlight-r"><pre>colnames(<span class="pl-vo">average_date</span>)[<span class="pl-c1">2</span>] <span class="pl-k">&lt;-</span> <span class="pl-s1"><span class="pl-pds">"</span>intervalAvg<span class="pl-pds">"</span></span></pre></div>

<h2>
<a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<div class="highlight highlight-r"><pre><span class="pl-c"># missing values</span>
sum(is.na(<span class="pl-vo">data</span><span class="pl-k">$</span><span class="pl-vo">steps</span>))</pre></div>

<pre><code>## [1] 2304
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-c"># Imputing NA's with average on 5-min interval</span>
<span class="pl-vo">merged</span> <span class="pl-k">&lt;-</span> arrange(join(<span class="pl-vo">data</span>, <span class="pl-vo">average_date</span>), <span class="pl-vo">interval</span>)</pre></div>

<pre><code>## Joining by: interval
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-c"># the new dataset</span>
<span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">steps</span>[is.na(<span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)] <span class="pl-k">&lt;-</span> <span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">intervalAvg</span>[is.na(<span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)]
<span class="pl-c"># plot the histogram</span>
<span class="pl-vo">new_daily_steps</span> <span class="pl-k">&lt;-</span> ddply(<span class="pl-vo">merged</span>, .(<span class="pl-vo">date</span>), <span class="pl-vo">summarise</span>, <span class="pl-v">steps</span> <span class="pl-k">=</span> sum(<span class="pl-vo">steps</span>))
hist(<span class="pl-vo">new_daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>, <span class="pl-v">main</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>Number of Steps<span class="pl-pds">"</span></span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>steps taken each day<span class="pl-pds">"</span></span>, 
    , )</pre></div>

<p><a href="/zacks1/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-4.png" target="_blank"><img src="/zacks1/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-4.png" alt="plot of chunk unnamed-chunk-4" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre><span class="pl-c"># mean and median total number of steps taken per day don't change</span>
<span class="pl-c"># significantly</span>
mean(<span class="pl-vo">new_daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-r"><pre>median(<span class="pl-vo">new_daily_steps</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-r"><pre><span class="pl-vo">daily_steps_1</span> <span class="pl-k">&lt;-</span> sum(<span class="pl-vo">data_waNA</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)
<span class="pl-vo">daily_steps_2</span> <span class="pl-k">&lt;-</span> sum(<span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">steps</span>)
<span class="pl-vo">diff</span> <span class="pl-k">&lt;-</span> <span class="pl-vo">daily_steps_2</span> <span class="pl-k">-</span> <span class="pl-vo">daily_steps_1</span>[]</pre></div>

<p>Mean values didn't change as imputation used the average on 5-mi interval</p>

<h2>
<a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<div class="highlight highlight-r"><pre>library(<span class="pl-vo">lattice</span>)
<span class="pl-vo">weekdays</span> <span class="pl-k">&lt;-</span> weekdays(as.Date(<span class="pl-vo">merged</span><span class="pl-k">$</span><span class="pl-vo">date</span>))
<span class="pl-vo">data_weekdays</span> <span class="pl-k">&lt;-</span> transform(<span class="pl-vo">merged</span>, <span class="pl-v">day</span> <span class="pl-k">=</span> <span class="pl-vo">weekdays</span>)
<span class="pl-vo">data_weekdays</span><span class="pl-k">$</span><span class="pl-vo">wk</span> <span class="pl-k">&lt;-</span> ifelse(<span class="pl-vo">data_weekdays</span><span class="pl-k">$</span><span class="pl-vo">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s1"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s1"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>), <span class="pl-s1"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>, 
    <span class="pl-s1"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>)
<span class="pl-vo">average_week</span> <span class="pl-k">&lt;-</span> ddply(<span class="pl-vo">data_weekdays</span>, .(<span class="pl-vo">interval</span>, <span class="pl-vo">wk</span>), <span class="pl-vo">summarise</span>, <span class="pl-v">steps</span> <span class="pl-k">=</span> mean(<span class="pl-vo">steps</span>))

xyplot(<span class="pl-vo">steps</span> <span class="pl-k">~</span> <span class="pl-vo">interval</span> <span class="pl-k">|</span> <span class="pl-vo">wk</span>, <span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-vo">average_week</span>, <span class="pl-v">layout</span> <span class="pl-k">=</span> c(<span class="pl-c1">1</span>, <span class="pl-c1">2</span>), <span class="pl-v">type</span> <span class="pl-k">=</span> <span class="pl-s1"><span class="pl-pds">"</span>l<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/zacks1/RepData_PeerAssessment1/blob/master/figure/unnamed-chunk-5.png" target="_blank"><img src="/zacks1/RepData_PeerAssessment1/raw/master/figure/unnamed-chunk-5.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a> </p>
</article>
  </div>

  </div>
</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" class="js-jump-to-line-form">
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="button">Go</button>
  </form>
</div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
      <li><a href="https://status.github.com/">Status</a></li>
      <li><a href="https://developer.github.com">API</a></li>
      <li><a href="http://training.github.com">Training</a></li>
      <li><a href="http://shop.github.com">Shop</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/about">About</a></li>

    </ul>

    <a href="/" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
    </a>

    <ul class="site-footer-links">
      <li>&copy; 2014 <span title="0.06353s from github-fe120-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="/site/terms">Terms</a></li>
        <li><a href="/site/privacy">Privacy</a></li>
        <li><a href="/security">Security</a></li>
        <li><a href="/contact">Contact</a></li>
    </ul>
  </div><!-- /.site-footer -->
</div><!-- /.container -->


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-153d6254b838872c8db73c8bd92905913f6f5b2164b7e40e5292286bd5a39403.js" type="text/javascript"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-f4947a80dc89b7b7941d65654d67ea6d87fb3f3baf28a2975462979455f8dcbe.js" type="text/javascript"></script>
      
      
  </body>
</html>

