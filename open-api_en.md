<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<meta content="IE=edge" http-equiv="X-UA-Compatible">
<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="open-api_en.md · 6bd015b0c65d33cf5a8b7b71e71749e30a8ae828 · java / open-api" property="og:title">
<meta content="open-api" property="og:description">
<meta content="http://git.gbc.mn/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="64" property="og:image:width">
<meta content="64" property="og:image:height">
<meta content="http://git.gbc.mn/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="open-api_en.md · 6bd015b0c65d33cf5a8b7b71e71749e30a8ae828 · java / open-api" property="twitter:title">
<meta content="open-api" property="twitter:description">
<meta content="http://git.gbc.mn/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>open-api_en.md · 6bd015b0c65d33cf5a8b7b71e71749e30a8ae828 · java / open-api · GitLab</title>
<meta content="open-api" name="description">
<link rel="shortcut icon" type="image/x-icon" href="/assets/favicon-075eba76312e8421991a0c1f89a89ee81678bcde72319dd3e8047e2a47cd3a42.ico" id="favicon" />
<link rel="stylesheet" media="all" href="/assets/application-57726da9781d5ef0948fcad9ebe5469811d0e1364f801a150d970f5ac55af44e.css" />
<link rel="stylesheet" media="print" href="/assets/print-74b3d49adeaada27337e759b75a34af7cf3d80051de91d60d40570f5a382e132.css" />


<script>
//<![CDATA[
window.gon={};gon.api_version="v4";gon.default_avatar_url="http:\/\/git.gbc.mn\/assets\/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png";gon.max_file_size=10;gon.asset_host=null;gon.webpack_public_path="\/assets\/webpack\/";gon.relative_url_root="";gon.shortcuts_path="\/help\/shortcuts";gon.user_color_scheme="white";gon.gitlab_url="http:\/\/git.gbc.mn";gon.revision="3e3c05b";gon.gitlab_logo="\/assets\/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png";gon.sprite_icons="\/assets\/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg";gon.sprite_file_icons="\/assets\/file_icons-7262fc6897e02f1ceaf8de43dc33afa5e4f9a2067f4f68ef77dcc87946575e9e.svg";gon.test_env=false;gon.suggested_label_colors=["#0033CC","#428BCA","#44AD8E","#A8D695","#5CB85C","#69D100","#004E00","#34495E","#7F8C8D","#A295D6","#5843AD","#8E44AD","#FFECDB","#AD4363","#D10069","#CC0033","#FF0000","#D9534F","#D1D100","#F0AD4E","#AD8D43"];gon.current_user_id=1;gon.current_username="root";gon.current_user_fullname="Administrator";gon.current_user_avatar_url="https:\/\/www.gravatar.com\/avatar\/e64c7d89f26bd1972efa854d13d7dd61?s=80\u0026d=identicon";
//]]>
</script>

<script src="/assets/webpack/webpack_runtime.bf993a5b9d06faed3c70.bundle.js" defer="defer"></script>
<script src="/assets/webpack/common.db159cd75479db13c6a5.bundle.js" defer="defer"></script>
<script src="/assets/webpack/main.7539c74898ef3ae85a9a.bundle.js" defer="defer"></script>

<script src="/assets/webpack/pages.projects.01592773ca8dd5701db7.bundle.js" defer="defer"></script>
<script src="/assets/webpack/pages.projects.blob.show.c156a41fbff24f4bce1a.bundle.js" defer="defer"></script>
<script>
  window.uploads_path = "/java/open-api/uploads";
</script>

<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="t2ydvW3VK3UkHXyoKetlIN8fggfEfjz2vx3iyNsdPYh4lgfme3jVN6WnI8SNU1fvYLDqLmot5R052sE31pv9DQ==" />
<meta content="origin-when-cross-origin" name="referrer">
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">



</head>

<body class="ui_indigo " data-find-file="/java/open-api/find_file/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828" data-group="" data-page="projects:blob:show" data-project="open-api">


<header class="navbar navbar-gitlab qa-navbar">
<a class="sr-only gl-accessibility" href="#content-body" tabindex="1">Skip to content</a>
<div class="container-fluid">
<div class="header-content">
<div class="title-container">
<h1 class="title">
<a title="Dashboard" id="logo" href="/"><svg width="24" height="24" class="tanuki-logo" viewBox="0 0 36 36">
  <path class="tanuki-shape tanuki-left-ear" fill="#e24329" d="M2 14l9.38 9v-9l-4-12.28c-.205-.632-1.176-.632-1.38 0z"/>
  <path class="tanuki-shape tanuki-right-ear" fill="#e24329" d="M34 14l-9.38 9v-9l4-12.28c.205-.632 1.176-.632 1.38 0z"/>
  <path class="tanuki-shape tanuki-nose" fill="#e24329" d="M18,34.38 3,14 33,14 Z"/>
  <path class="tanuki-shape tanuki-left-eye" fill="#fc6d26" d="M18,34.38 11.38,14 2,14 6,25Z"/>
  <path class="tanuki-shape tanuki-right-eye" fill="#fc6d26" d="M18,34.38 24.62,14 34,14 30,25Z"/>
  <path class="tanuki-shape tanuki-left-cheek" fill="#fca326" d="M2 14L.1 20.16c-.18.565 0 1.2.5 1.56l17.42 12.66z"/>
  <path class="tanuki-shape tanuki-right-cheek" fill="#fca326" d="M34 14l1.9 6.16c.18.565 0 1.2-.5 1.56L18 34.38z"/>
</svg>

<span class="logo-text hidden-xs">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 617 169"><path d="M315.26 2.97h-21.8l.1 162.5h88.3v-20.1h-66.5l-.1-142.4M465.89 136.95c-5.5 5.7-14.6 11.4-27 11.4-16.6 0-23.3-8.2-23.3-18.9 0-16.1 11.2-23.8 35-23.8 4.5 0 11.7.5 15.4 1.2v30.1h-.1m-22.6-98.5c-17.6 0-33.8 6.2-46.4 16.7l7.7 13.4c8.9-5.2 19.8-10.4 35.5-10.4 17.9 0 25.8 9.2 25.8 24.6v7.9c-3.5-.7-10.7-1.2-15.1-1.2-38.2 0-57.6 13.4-57.6 41.4 0 25.1 15.4 37.7 38.7 37.7 15.7 0 30.8-7.2 36-18.9l4 15.9h15.4v-83.2c-.1-26.3-11.5-43.9-44-43.9M557.63 149.1c-8.2 0-15.4-1-20.8-3.5V70.5c7.4-6.2 16.6-10.7 28.3-10.7 21.1 0 29.2 14.9 29.2 39 0 34.2-13.1 50.3-36.7 50.3m9.2-110.6c-19.5 0-30 13.3-30 13.3v-21l-.1-27.8h-21.3l.1 158.5c10.7 4.5 25.3 6.9 41.2 6.9 40.7 0 60.3-26 60.3-70.9-.1-35.5-18.2-59-50.2-59M77.9 20.6c19.3 0 31.8 6.4 39.9 12.9l9.4-16.3C114.5 6 97.3 0 78.9 0 32.5 0 0 28.3 0 85.4c0 59.8 35.1 83.1 75.2 83.1 20.1 0 37.2-4.7 48.4-9.4l-.5-63.9V75.1H63.6v20.1h38l.5 48.5c-5 2.5-13.6 4.5-25.3 4.5-32.2 0-53.8-20.3-53.8-63-.1-43.5 22.2-64.6 54.9-64.6M231.43 2.95h-21.3l.1 27.3v94.3c0 26.3 11.4 43.9 43.9 43.9 4.5 0 8.9-.4 13.1-1.2v-19.1c-3.1.5-6.4.7-9.9.7-17.9 0-25.8-9.2-25.8-24.6v-65h35.7v-17.8h-35.7l-.1-38.5M155.96 165.47h21.3v-124h-21.3v124M155.96 24.37h21.3V3.07h-21.3v21.3"/></svg>

</span>
</a></h1>
<ul class="list-unstyled navbar-sub-nav">
<li id="nav-projects-dropdown" class="home dropdown header-projects qa-projects-dropdown"><a data-toggle="dropdown" href="#">
Projects
<svg class=" caret-down"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-down"></use></svg>
</a>
<div class="dropdown-menu projects-dropdown-menu">
<div class="projects-dropdown-container">
<div class="project-dropdown-sidebar qa-projects-dropdown-sidebar">
<ul>
<li class=""><a class="qa-your-projects-link" href="/dashboard/projects">Your projects
</a></li><li class=""><a href="/dashboard/projects/starred">Starred projects
</a></li><li class=""><a href="/explore">Explore projects
</a></li></ul>
</div>
<div class="project-dropdown-content">
<div data-project-id="38" data-project-name="open-api" data-project-namespace="java / open-api" data-project-web-url="/java/open-api" data-user-name="root" id="js-projects-dropdown"></div>
</div>
</div>

</div>
</li><li class="hidden-xs"><a class="dashboard-shortcuts-groups qa-groups-link" title="Groups" href="/dashboard/groups">Groups
</a></li><li class="visible-lg"><a class="dashboard-shortcuts-activity" title="Activity" href="/dashboard/activity">Activity
</a></li><li class="visible-lg"><a class="dashboard-shortcuts-milestones" title="Milestones" href="/dashboard/milestones">Milestones
</a></li><li class="visible-lg"><a class="dashboard-shortcuts-snippets" title="Snippets" href="/dashboard/snippets">Snippets
</a></li><li class="header-more dropdown hidden-lg">
<a data-toggle="dropdown" href="#">
More
<svg class=" caret-down"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-down"></use></svg>
</a>
<div class="dropdown-menu">
<ul>
<li class="visible-xs"><a class="dashboard-shortcuts-groups" title="Groups" href="/dashboard/groups">Groups
</a></li><li class=""><a title="Activity" href="/dashboard/activity">Activity
</a></li><li class=""><a class="dashboard-shortcuts-milestones" title="Milestones" href="/dashboard/milestones">Milestones
</a></li><li class=""><a class="dashboard-shortcuts-snippets" title="Snippets" href="/dashboard/snippets">Snippets
</a></li></ul>
</div>
</li>
<li class="hidden">
<a title="Projects" class="dashboard-shortcuts-projects" href="/dashboard/projects">Projects
</a></li>
<li class="line-separator hidden-xs"></li>
<li class=""><a class="admin-icon qa-admin-area-link" title="Admin area" aria-label="Admin area" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/admin"><svg class="s18"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#admin"></use></svg>
</a></li></ul>

</div>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="header-new dropdown">
<a class="header-new-dropdown-toggle has-tooltip qa-new-menu-toggle" title="New..." ref="tooltip" aria-label="New..." data-toggle="dropdown" data-placement="bottom" data-container="body" href="/projects/new"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#plus-square"></use></svg>
<svg class=" caret-down"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-down"></use></svg>
</a><div class="dropdown-menu-nav dropdown-menu-align-right">
<ul>
<li class="dropdown-bold-header">This project</li>
<li>
<a href="/java/open-api/issues/new">New issue</a>
</li>
<li>
<a href="/java/open-api/merge_requests/new">New merge request</a>
</li>
<li class="header-new-project-snippet">
<a href="/java/open-api/snippets/new">New snippet</a>
</li>
<li class="divider"></li>
<li class="dropdown-bold-header">GitLab</li>
<li>
<a href="/projects/new">New project</a>
</li>
<li>
<a href="/groups/new">New group</a>
</li>
<li>
<a href="/snippets/new">New snippet</a>
</li>
</ul>
</div>
</li>

<li class="hidden-sm hidden-xs">
<div class="has-location-badge search search-form">
<form class="navbar-form" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="location-badge">This project</div>
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search" class="search-input dropdown-menu-toggle no-outline js-search-dashboard-options" spellcheck="false" tabindex="1" autocomplete="off" data-issues-path="/dashboard/issues" data-mr-path="/dashboard/merge_requests" aria-label="Search" />
<button class="hidden js-dropdown-search-toggle" data-toggle="dropdown" type="button"></button>
<div class="dropdown-menu dropdown-select">
<div class="dropdown-content"><ul>
<li class="dropdown-menu-empty-item">
<a>
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
<svg class="s16 search-icon"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#search"></use></svg>
<svg class="s16 clear-icon js-clear-input"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" class="js-search-group-options" />
<input type="hidden" name="project_id" id="search_project_id" value="38" class="js-search-project-options" data-project-path="open-api" data-name="open-api" data-issues-path="/java/open-api/issues" data-mr-path="/java/open-api/merge_requests" data-issues-disabled="false" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<input type="hidden" name="repository_ref" id="repository_ref" value="6bd015b0c65d33cf5a8b7b71e71749e30a8ae828" />

<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="38" data-autocomplete-project-ref="6bd015b0c65d33cf5a8b7b71e71749e30a8ae828"></div>
</form></div>

</li>
<li class="visible-sm-inline-block visible-xs-inline-block">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#search"></use></svg>
</a></li>
<li class="user-counter"><a title="Issues" class="dashboard-shortcuts-issues" aria-label="Issues" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/issues?assignee_id=1"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#issues"></use></svg>
<span class="badge hidden issues-count">
0
</span>
</a></li><li class="user-counter"><a title="Merge requests" class="dashboard-shortcuts-merge_requests" aria-label="Merge requests" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/merge_requests?assignee_id=1"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#git-merge"></use></svg>
<span class="badge hidden merge-requests-count">
0
</span>
</a></li><li class="user-counter"><a title="Todos" aria-label="Todos" class="shortcuts-todos" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/dashboard/todos"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#todo-done"></use></svg>
<span class="badge hidden todos-count">
0
</span>
</a></li><li class="header-user dropdown">
<a class="header-user-dropdown-toggle" data-toggle="dropdown" href="/root"><img width="23" height="23" class="header-user-avatar qa-user-avatar lazy" data-src="https://www.gravatar.com/avatar/e64c7d89f26bd1972efa854d13d7dd61?s=46&amp;d=identicon" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
<svg class=" caret-down"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-down"></use></svg>
</a><div class="dropdown-menu-nav dropdown-menu-align-right">
<ul>
<li class="current-user">
<div class="user-name bold">
Administrator
</div>
@root
</li>
<li class="divider"></li>
<li>
<a class="profile-link" data-user="root" href="/root">Profile</a>
</li>
<li>
<a href="/profile">Settings</a>
</li>
<li>
<a href="/help">Help</a>
</li>
<li class="divider"></li>
<li>
<a class="sign-out-link" href="/users/sign_out">Sign out</a>
</li>
</ul>
</div>
</li>
</ul>
</div>
<button class="navbar-toggle hidden-sm hidden-md hidden-lg" type="button">
<span class="sr-only">Toggle navigation</span>
<svg class="s12 more-icon js-navbar-toggle-right"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#more"></use></svg>
<svg class="s12 close-icon js-navbar-toggle-left"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
</button>
</div>
</div>
</header>

<div class="layout-page page-with-contextual-sidebar">
<div class="nav-sidebar">
<div class="nav-sidebar-inner-scroll">
<div class="context-header">
<a title="open-api" href="/java/open-api"><div class="avatar-container s40 project-avatar">
<div class="avatar s40 avatar-tile identicon" style="background-color: #E3F2FD; color: #555">O</div>
</div>
<div class="sidebar-context-title">
open-api
</div>
</a></div>
<ul class="sidebar-top-level-items">
<li class="home"><a class="shortcuts-project" href="/java/open-api"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#project"></use></svg>
</div>
<span class="nav-item-name">
Overview
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/java/open-api"><strong class="fly-out-top-item-name">
Overview
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Project details" class="shortcuts-project" href="/java/open-api"><span>Details</span>
</a></li><li class=""><a title="Activity" class="shortcuts-project-activity" href="/java/open-api/activity"><span>Activity</span>
</a></li><li class=""><a title="Cycle Analytics" class="shortcuts-project-cycle-analytics" href="/java/open-api/cycle_analytics"><span>Cycle Analytics</span>
</a></li></ul>
</li><li class="active"><a class="shortcuts-tree" href="/java/open-api/tree/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#doc_text"></use></svg>
</div>
<span class="nav-item-name">
Repository
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item active"><a href="/java/open-api/tree/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828"><strong class="fly-out-top-item-name">
Repository
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class="active"><a href="/java/open-api/tree/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Files
</a></li><li class=""><a href="/java/open-api/commits/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Commits
</a></li><li class=""><a href="/java/open-api/branches">Branches
</a></li><li class=""><a href="/java/open-api/tags">Tags
</a></li><li class=""><a href="/java/open-api/graphs/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Contributors
</a></li><li class=""><a href="/java/open-api/network/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Graph
</a></li><li class=""><a href="/java/open-api/compare?from=master&amp;to=6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Compare
</a></li><li class=""><a href="/java/open-api/graphs/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/charts">Charts
</a></li></ul>
</li><li class=""><a class="shortcuts-issues" href="/java/open-api/issues"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#issues"></use></svg>
</div>
<span class="nav-item-name">
Issues
</span>
<span class="badge count issue_counter">
0
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/java/open-api/issues"><strong class="fly-out-top-item-name">
Issues
</strong>
<span class="badge count issue_counter fly-out-badge">
0
</span>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Issues" href="/java/open-api/issues"><span>
List
</span>
</a></li><li class=""><a title="Board" href="/java/open-api/boards"><span>
Board
</span>
</a></li><li class=""><a title="Labels" href="/java/open-api/labels"><span>
Labels
</span>
</a></li><li class=""><a title="Milestones" href="/java/open-api/milestones"><span>
Milestones
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-merge_requests" href="/java/open-api/merge_requests"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#git-merge"></use></svg>
</div>
<span class="nav-item-name">
Merge Requests
</span>
<span class="badge count merge_counter js-merge-counter">
0
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/java/open-api/merge_requests"><strong class="fly-out-top-item-name">
Merge Requests
</strong>
<span class="badge count merge_counter js-merge-counter fly-out-badge">
0
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-pipelines" href="/java/open-api/pipelines"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#pipeline"></use></svg>
</div>
<span class="nav-item-name">
CI / CD
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/java/open-api/pipelines"><strong class="fly-out-top-item-name">
CI / CD
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="Pipelines" class="shortcuts-pipelines" href="/java/open-api/pipelines"><span>
Pipelines
</span>
</a></li><li class=""><a title="Jobs" class="shortcuts-builds" href="/java/open-api/-/jobs"><span>
Jobs
</span>
</a></li><li class=""><a title="Schedules" class="shortcuts-builds" href="/java/open-api/pipeline_schedules"><span>
Schedules
</span>
</a></li><li class=""><a title="Environments" class="shortcuts-environments" href="/java/open-api/environments"><span>
Environments
</span>
</a></li><li class=""><a title="Kubernetes" class="shortcuts-cluster" href="/java/open-api/clusters"><span>
Kubernetes
</span>
<div class="feature-highlight js-feature-highlight" data-container="body" data-dismiss-endpoint="/-/user_callouts" data-highlight="gke_cluster_integration" data-placement="right" data-toggle="popover" data-trigger="manual" disabled></div>
</a><div class="feature-highlight-popover-content">
<img class="feature-highlight-illustration lazy" data-src="/assets/illustrations/cluster_popover-9830388038d966d8d64d43576808f9d5ba05f639a78a40bae9a5ddc7cbf72f24.svg" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
<div class="feature-highlight-popover-sub-content">
<p>Allows you to add and manage Kubernetes clusters.</p>
<p>
Protip:
<a href="/help/topics/autodevops/index.md">Auto DevOps</a>
<span>uses Kubernetes clusters to deploy your code!</span>
</p>
<hr>
<button class="btn btn-create btn-xs dismiss-feature-highlight" type="button">
<span>Got it!</span>
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#thumb-up"></use></svg>
</button>
</div>
</div>
</li><li class=""><a title="Charts" class="shortcuts-pipelines-charts" href="/java/open-api/pipelines/charts"><span>
Charts
</span>
</a></li></ul>
</li><li class=""><a class="shortcuts-wiki" href="/java/open-api/wikis/home"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#book"></use></svg>
</div>
<span class="nav-item-name">
Wiki
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/java/open-api/wikis/home"><strong class="fly-out-top-item-name">
Wiki
</strong>
</a></li></ul>
</li><li class=""><a class="shortcuts-snippets" href="/java/open-api/snippets"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#snippet"></use></svg>
</div>
<span class="nav-item-name">
Snippets
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a href="/java/open-api/snippets"><strong class="fly-out-top-item-name">
Snippets
</strong>
</a></li></ul>
</li><li class=""><a class="shortcuts-tree" href="/java/open-api/edit"><div class="nav-icon-container">
<svg><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#settings"></use></svg>
</div>
<span class="nav-item-name qa-settings-item">
Settings
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a href="/java/open-api/edit"><strong class="fly-out-top-item-name">
Settings
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a title="General" href="/java/open-api/edit"><span>
General
</span>
</a></li><li class=""><a title="Members" href="/java/open-api/project_members"><span>
Members
</span>
</a></li><li class=""><a title="Integrations" href="/java/open-api/settings/integrations"><span>
Integrations
</span>
</a></li><li class=""><a title="Repository" href="/java/open-api/settings/repository"><span>
Repository
</span>
</a></li><li class=""><a title="CI / CD" href="/java/open-api/settings/ci_cd"><span>
CI / CD
</span>
</a></li></ul>
</li><a class="toggle-sidebar-button js-toggle-sidebar" role="button" title="Toggle sidebar" type="button">
<svg class=" icon-angle-double-left"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-double-left"></use></svg>
<svg class=" icon-angle-double-right"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-double-right"></use></svg>
<span class="collapse-text">Collapse sidebar</span>
</a>
<button name="button" type="button" class="close-nav-button"><svg class="s16"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#close"></use></svg>
<span class="collapse-text">Close sidebar</span>
</button>
<li class="hidden">
<a title="Activity" class="shortcuts-project-activity" href="/java/open-api/activity"><span>
Activity
</span>
</a></li>
<li class="hidden">
<a title="Network" class="shortcuts-network" href="/java/open-api/network/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Graph
</a></li>
<li class="hidden">
<a title="Charts" class="shortcuts-repository-charts" href="/java/open-api/graphs/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/charts">Charts
</a></li>
<li class="hidden">
<a class="shortcuts-new-issue" href="/java/open-api/issues/new">Create a new issue
</a></li>
<li class="hidden">
<a title="Jobs" class="shortcuts-builds" href="/java/open-api/-/jobs">Jobs
</a></li>
<li class="hidden">
<a title="Commits" class="shortcuts-commits" href="/java/open-api/commits/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">Commits
</a></li>
<li class="hidden">
<a title="Issue Boards" class="shortcuts-issue-boards" href="/java/open-api/boards">Issue Boards</a>
</li>
</ul>
</div>
</div>

<div class="content-wrapper">

<div class="mobile-overlay"></div>
<div class="alert-wrapper">


<nav class="breadcrumbs container-fluid container-limited" role="navigation">
<div class="breadcrumbs-container">
<button name="button" type="button" class="toggle-mobile-nav"><span class="sr-only">Open sidebar</span>
<i aria-hidden="true" data-hidden="true" class="fa fa-bars"></i>
</button><div class="breadcrumbs-links js-title-container">
<ul class="list-unstyled breadcrumbs-list js-breadcrumbs-list">
<li><a class="group-path breadcrumb-item-text js-breadcrumb-item-text " href="/java">java</a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-right"></use></svg></li> <li><a href="/java/open-api"><span class="breadcrumb-item-text js-breadcrumb-item-text">open-api</span></a><svg class="s8 breadcrumbs-list-angle"><use xlink:href="/assets/icons-2666da8eb968ba69467c0369d020bf011a5d0b1bd253ba0dbcc43bd0ccbd0dcb.svg#angle-right"></use></svg></li>

<li>
<h2 class="breadcrumbs-sub-title"><a href="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md">Repository</a></h2>
</li>
</ul>
</div>

</div>
</nav>

<div class="flash-container flash-container-page">
</div>

</div>
<div class=" ">
<div class="content" id="content-body">
<div class="container-fluid container-limited">

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-container">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/java/open-api/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="open-api_en.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown" type="button" data-toggle="dropdown" data-selected="6bd015b0c65d33cf5a8b7b71e71749e30a8ae828" data-ref="6bd015b0c65d33cf5a8b7b71e71749e30a8ae828" data-refs-url="/java/open-api/refs?sort=updated_desc" data-field-name="ref" data-submit-form-on-click="true" data-visit="true"><span class="dropdown-toggle-text ">6bd015b0c65d33cf5a8b7b71e71749e30a8ae828</span><i aria-hidden="true" data-hidden="true" class="fa fa-chevron-down"></i></button>
<div class="dropdown-menu dropdown-menu-paging dropdown-menu-selectable git-revision-dropdown">
<div class="dropdown-page-one">
<div class="dropdown-title"><span>Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close" aria-label="Close" type="button"><i aria-hidden="true" data-hidden="true" class="fa fa-times dropdown-menu-close-icon"></i></button></div>
<div class="dropdown-input"><input type="search" id="" class="dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><i aria-hidden="true" data-hidden="true" class="fa fa-search dropdown-input-search"></i><i role="button" aria-hidden="true" data-hidden="true" class="fa fa-times dropdown-input-clear js-dropdown-input-clear"></i></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><i aria-hidden="true" data-hidden="true" class="fa fa-spinner fa-spin"></i></div>
</div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li>
<a href="/java/open-api/tree/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828">open-api
</a></li>
<li>
<a href="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md"><strong>open-api_en.md</strong>
</a></li>
</ul>
</div>
<div class="tree-controls">
<a class="btn shortcuts-find-file" rel="nofollow" href="/java/open-api/find_file/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828"><i aria-hidden="true" data-hidden="true" class="fa fa-search"></i>
<span>Find file</span>
</a>
<div class="btn-group" role="group"><a class="btn js-blob-blame-link" href="/java/open-api/blame/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md">Blame</a><a class="btn" href="/java/open-api/commits/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md">History</a><a class="btn js-data-file-blob-permalink-url" href="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md">Permalink</a></div>
</div>
</div>

<div class="info-well hidden-xs">
<div class="well-segment">
<ul class="blob-commit-info">
<li class="commit flex-row js-toggle-container" id="commit-90f0443c">
<div class="avatar-cell hidden-xs">
<a href="/guanxi"><img alt="seal kwan&#39;s avatar" src="https://www.gravatar.com/avatar/5b4175bc661caefb0b01ad5239832076?s=72&amp;d=identicon" data-container="body" class="avatar s36 hidden-xs has-tooltip" title="seal kwan" /></a>
</div>
<div class="commit-detail flex-list">
<div class="commit-content">
<a class="commit-row-message item-title" href="/java/open-api/commit/90f0443c5df5781299df2c6d8493e98c5639a381">Update open-api_en.md</a>
<span class="commit-row-message visible-xs-inline">
&middot;
90f0443c
</span>
<div class="commiter">
<a class="commit-author-link has-tooltip" title="fsolsh@qq.com" href="/guanxi">seal kwan</a> authored <time class="js-timeago" title="Sep 4, 2018 10:21am" datetime="2018-09-04T10:21:43Z" data-toggle="tooltip" data-placement="bottom" data-container="body">Sep 04, 2018</time>
</div>
</div>
<div class="commit-actions flex-row hidden-xs">

<div class="js-commit-pipeline-status" data-endpoint="/java/open-api/commit/90f0443c5df5781299df2c6d8493e98c5639a381/pipelines"></div>
<a class="commit-sha btn btn-transparent btn-link" href="/java/open-api/commit/90f0443c5df5781299df2c6d8493e98c5639a381">90f0443c</a>
<button class="btn btn-clipboard btn-transparent" data-toggle="tooltip" data-placement="bottom" data-container="body" data-title="Copy commit SHA to clipboard" data-clipboard-text="90f0443c5df5781299df2c6d8493e98c5639a381" type="button" title="Copy commit SHA to clipboard" aria-label="Copy commit SHA to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button>

</div>
</div>
</li>

</ul>
</div>

</div>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="js-file-title file-title-flex-parent">
<div class="file-header-content">
<i aria-hidden="true" data-hidden="true" class="fa fa-file-text-o fa-fw"></i>
<strong class="file-title-name">
open-api_en.md
</strong>
<button class="btn btn-clipboard btn-transparent prepend-left-5" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn-clipboard btn-transparent prepend-left-5" data-title="Copy file path to clipboard" data-clipboard-text="{&quot;text&quot;:&quot;open-api_en.md&quot;,&quot;gfm&quot;:&quot;`open-api_en.md`&quot;}" type="button" title="Copy file path to clipboard" aria-label="Copy file path to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button>
<small>
16.5 KB
</small>
</div>

<div class="file-actions">
<div class="btn-group js-blob-viewer-switcher" role="group">
<button aria-label="Display source" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="simple" title="Display source">
<i aria-hidden="true" data-hidden="true" class="fa fa-code"></i>
</button><button aria-label="Display rendered file" class="btn btn-default btn-sm js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="rich" title="Display rendered file">
<i aria-hidden="true" data-hidden="true" class="fa fa-file-text-o"></i>
</button></div>

<div class="btn-group" role="group"><button class="btn btn btn-sm js-copy-blob-source-btn" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="btn btn-sm js-copy-blob-source-btn" data-title="Copy source to clipboard" data-clipboard-target=".blob-content[data-blob-id=&#39;08174a82804d03e5e86f15f71ba31bfc915dfa46&#39;]" type="button" title="Copy source to clipboard" aria-label="Copy source to clipboard"><i aria-hidden="true" aria-hidden="true" data-hidden="true" class="fa fa-clipboard"></i></button><a class="btn btn-sm has-tooltip" target="_blank" rel="noopener noreferrer" title="Open raw" data-container="body" href="/java/open-api/raw/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md"><i aria-hidden="true" data-hidden="true" class="fa fa-file-code-o"></i></a></div>
<div class="btn-group" role="group"><button name="button" type="submit" class="btn js-edit-blob  disabled has-tooltip" title="You can only edit files when you are on a branch" data-container="body">Edit</button><button name="button" type="submit" class="btn btn-default disabled has-tooltip" title="You can only replace files when you are on a branch" data-container="body">Replace</button><button name="button" type="submit" class="btn btn-remove disabled has-tooltip" title="You can only delete files when you are on a branch" data-container="body">Delete</button></div>
</div>
</div>
<div class="js-file-fork-suggestion-section file-fork-suggestion hidden">
<span class="file-fork-suggestion-note">
You're not allowed to
<span class="js-file-fork-suggestion-section-action">
edit
</span>
files in this project directly. Please fork this project,
make your changes there, and submit a merge request.
</span>
<a class="js-fork-suggestion-button btn btn-grouped btn-inverted btn-new" rel="nofollow" data-method="post" href="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md">Fork</a>
<button class="js-cancel-fork-suggestion-button btn btn-grouped" type="button">
Cancel
</button>
</div>


<div class="blob-viewer hidden" data-type="simple" data-url="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md?format=json&amp;viewer=simple">
<div class="text-center prepend-top-default append-bottom-default">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x"></i>
</div>

</div>

<div class="blob-viewer" data-rich-type="markup" data-type="rich" data-url="/java/open-api/blob/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md?format=json&amp;viewer=rich">
<div class="text-center prepend-top-default append-bottom-default">
<i aria-hidden="true" aria-label="Loading content…" class="fa fa-spinner fa-spin fa-2x"></i>
</div>

</div>


</article>
</div>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<a class="close" data-dismiss="modal" href="#">&times;</a>
<h3 class="page-title">Replace open-api_en.md</h3>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form form-horizontal" data-method="put" action="/java/open-api/update/6bd015b0c65d33cf5a8b7b71e71749e30a8ae828/open-api_en.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="Uz/e9kuN/YNmQYWJxm6J+VetWI8yxzyoKa8JMAvpOaycxUStXSADwef72uVi1rs26AIwppyU5UOvaCrPBm/5KQ==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or <a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="dropzone-alerts alert alert-danger data" style="display:none"></div>
<div class="form-group commit_message-group">
<label class="control-label" for="commit_message-c1382e58eaa7265b9f7aa98ab28a0192">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-c1382e58eaa7265b9f7aa98ab28a0192" class="form-control js-commit-message" placeholder="Replace open-api_en.md" required="required" rows="3">
Replace open-api_en.md</textarea>
</div>
</div>
</div>

<div class="form-group branch">
<label class="control-label" for="branch_name">Target Branch</label>
<div class="col-sm-10">
<input type="text" name="branch_name" id="branch_name" required="required" class="form-control js-branch-name ref-name" />
<div class="js-create-merge-request-container">
<div class="checkbox">
<label for="create_merge_request-d96d47da1361552bcbf34aea936242e2"><input type="checkbox" name="create_merge_request" id="create_merge_request-d96d47da1361552bcbf34aea936242e2" value="1" class="js-create-merge-request" checked="checked" />
Start a <strong>new merge request</strong> with these changes
</label></div>

</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="6bd015b0c65d33cf5a8b7b71e71749e30a8ae828" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="button" class="btn btn-create btn-upload-file" id="submit-all"><i aria-hidden="true" data-hidden="true" class="fa fa-spin fa-spinner js-loading-icon hidden"></i>
Replace file
</button><a class="btn btn-cancel" data-dismiss="modal" href="#">Cancel</a>

</div>
</form></div>
</div>
</div>
</div>

</div>
</div>

</div>
</div>
</div>
</div>


</body>
</html>
