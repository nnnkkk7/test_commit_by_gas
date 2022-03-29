head>
    <meta name="google-signin-client-id" content="721724668570-nbkv1cfusk7kk4eni4pjvepaus73b13t.apps.googleusercontent.com">
    <meta name="google-signin-scope"
          content="profile email https://www.googleapis.com/auth/developerprofiles https://www.googleapis.com/auth/developerprofiles.award">
    <meta property="og:site_name" content="Google Developers">
    <meta property="og:type" content="website"><meta name="theme-color" content="#ffffff"><meta charset="utf-8">
    <meta content="IE=Edge" http-equiv="X-UA-Compatible">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    

    <link rel="manifest" href="/_pwa/developers/manifest.json"
          crossorigin="use-credentials">
    <link rel="preconnect" href="//www.gstatic.com" crossorigin>
    <link rel="preconnect" href="//fonts.gstatic.com" crossorigin>
    <link rel="preconnect" href="//fonts.googleapis.com" crossorigin>
    <link rel="preconnect" href="//apis.google.com" crossorigin>
    <link rel="preconnect" href="//www.google-analytics.com" crossorigin><link rel="stylesheet" href="//fonts.googleapis.com/css?family=Google+Sans:400,500|Roboto:400,400italic,500,500italic,700,700italic|Roboto+Mono:400,500,700&display=swap">
      <link rel="stylesheet" href="//fonts.googleapis.com/css?family=Material+Icons&display=block"><link rel="stylesheet" href="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/css/app.css">
      <link rel="shortcut icon" href="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/images/favicon.png">
    <link rel="apple-touch-icon" href="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/images/touchicon-180.png"><link rel="canonical" href="https://developers.google.com/my-business/content/policies"><link rel="search" type="application/opensearchdescription+xml"
            title="Google Developers" href="https://developers.google.com/s/opensearch.xml">
      

<title>Google Business Profile APIs &nbsp;|&nbsp; Google Developers</title>

<meta property="og:title" content="Google Business Profile APIs &nbsp;|&nbsp; Google Developers"><meta property="og:url" content="https://developers.google.com/my-business/content/policies"><meta property="og:image" content="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/images/opengraph/white.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="675"><meta property="og:locale" content="en"><meta name="twitter:card" content="summary_large_image">
  

  

  

  


    </head>
  <body class=""
        template="page"
        theme="white"
        type="article"
        
        
        layout="docs"
        
        
        pending>
    <devsite-progress type="indeterminate" id="app-progress"></devsite-progress>
  
    <section class="devsite-wrapper"><devsite-header>
  
    























<div class="devsite-header--inner nocontent">
  <div class="devsite-top-logo-row-wrapper-wrapper">
    <div class="devsite-top-logo-row-wrapper">
      <div class="devsite-top-logo-row">
        <button type="button" id="devsite-hamburger-menu"
          class="devsite-header-icon-button button-flat material-icons gc-analytics-event"
          data-category="Site-Wide Custom Events"
          data-label="Navigation menu button"
          visually-hidden
          aria-label="Open menu">
        </button>
        <div class="devsite-product-name-wrapper">

  
    
  



  
  
  <span class="devsite-product-name">
    <ul class="devsite-breadcrumb-list"
  >
  
  <li class="devsite-breadcrumb-item
             devsite-has-google-wordmark">
    
    
    
      
      
        
  <a href="https://developers.google.com/my-business"
      
        class="devsite-breadcrumb-link gc-analytics-event"
      
        data-category="Site-Wide Custom Events"
      
        data-label="Upper Header"
      
        data-value="1"
      
        track-type="globalNav"
      
        track-name="breadcrumb"
      
        track-metadata-position="1"
      
        track-metadata-eventdetail="Google Business Profile APIs"
      
    >
    
          <svg class="devsite-google-wordmark"
       xmlns="http://www.w3.org/2000/svg"
       viewBox="0 0 148 48">
    <title>Google</title>
    <path class="devsite-google-wordmark-svg-path" d="M19.58,37.65c-9.87,0-18.17-8.04-18.17-17.91c0-9.87,8.3-17.91,18.17-17.91c5.46,0,9.35,2.14,12.27,4.94l-3.45,3.45c-2.1-1.97-4.93-3.49-8.82-3.49c-7.21,0-12.84,5.81-12.84,13.02c0,7.21,5.64,13.02,12.84,13.02c4.67,0,7.34-1.88,9.04-3.58c1.4-1.4,2.32-3.41,2.66-6.16H19.58v-4.89h16.47c0.18,0.87,0.26,1.92,0.26,3.06c0,3.67-1.01,8.21-4.24,11.44C28.93,35.9,24.91,37.65,19.58,37.65z M61.78,26.12c0,6.64-5.1,11.53-11.36,11.53s-11.36-4.89-11.36-11.53c0-6.68,5.1-11.53,11.36-11.53S61.78,19.43,61.78,26.12z M56.8,26.12c0-4.15-2.96-6.99-6.39-6.99c-3.43,0-6.39,2.84-6.39,6.99c0,4.11,2.96,6.99,6.39,6.99C53.84,33.11,56.8,30.22,56.8,26.12z M87.25,26.12c0,6.64-5.1,11.53-11.36,11.53c-6.26,0-11.36-4.89-11.36-11.53c0-6.68,5.1-11.53,11.36-11.53C82.15,14.59,87.25,19.43,87.25,26.12zM82.28,26.12c0-4.15-2.96-6.99-6.39-6.99c-3.43,0-6.39,2.84-6.39,6.99c0,4.11,2.96,6.99,6.39,6.99C79.32,33.11,82.28,30.22,82.28,26.12z M112.09,15.29v20.7c0,8.52-5.02,12.01-10.96,12.01c-5.59,0-8.95-3.76-10.22-6.81l4.41-1.83c0.79,1.88,2.71,4.1,5.81,4.1c3.8,0,6.16-2.36,6.16-6.77v-1.66h-0.18c-1.14,1.4-3.32,2.62-6.07,2.62c-5.76,0-11.05-5.02-11.05-11.49c0-6.51,5.28-11.57,11.05-11.57c2.75,0,4.93,1.22,6.07,2.58h0.18v-1.88H112.09z M107.64,26.16c0-4.06-2.71-7.03-6.16-7.03c-3.49,0-6.42,2.97-6.42,7.03c0,4.02,2.93,6.94,6.42,6.94C104.93,33.11,107.64,30.18,107.64,26.16z M120.97,3.06v33.89h-5.07V3.06H120.97z M140.89,29.92l3.93,2.62c-1.27,1.88-4.32,5.11-9.61,5.11c-6.55,0-11.28-5.07-11.28-11.53c0-6.86,4.77-11.53,10.71-11.53c5.98,0,8.91,4.76,9.87,7.34l0.52,1.31l-15.42,6.38c1.18,2.31,3.01,3.49,5.59,3.49C137.79,33.11,139.58,31.84,140.89,29.92zM128.79,25.77l10.31-4.28c-0.57-1.44-2.27-2.45-4.28-2.45C132.24,19.04,128.66,21.31,128.79,25.77z"/>
  </svg>Business Profile APIs
        
  </a>
  
      
    
  </li>
  
</ul>
  </span>

