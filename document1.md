dir="ltr">
  <head>
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
    <link rel="apple-touch-icon" href="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/images/touchicon-180.png"><link rel="canonical" href="https://developers.google.com/my-business/content/accountmanagement/change-log"><link rel="search" type="application/opensearchdescription+xml"
            title="Google Developers" href="https://developers.google.com/s/opensearch.xml">
      

<title>Account Management API &nbsp;|&nbsp; Google Business Profile APIs &nbsp;|&nbsp; Google Developers</title>

<meta property="og:title" content="Account Management API &nbsp;|&nbsp; Google Business Profile APIs &nbsp;|&nbsp; Google Developers"><meta property="og:url" content="https://developers.google.com/my-business/content/accountmanagement/change-log"><meta property="og:image" content="https://www.gstatic.com/devrel-devsite/prod/vc705ce9bd51279e80f03a51aec7c6eb1f05e56e75c958618655fc719098c9888/developers/images/opengraph/white.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="675"><meta property="og:locale" content="en"><meta name="twitter:card" content="summary_large_image"><script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "BreadcrumbList",
    "itemListElement": [{
      "@type": "ListItem",
      "position": 1,
      "name": "Business Profile APIs",
      "item": "https://developers.google.com/my-business"
    },{
      "@type": "ListItem",
      "position": 2,
      "name": "Account Management API",
      "item": "https://developers.google.com/my-business/content/accountmanagement/change-log"
    }]
  }
  </script>
  

  

  


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

</div>
        <div class="devsite-top-logo-row-middle">
          <div class="devsite-header-upper-tabs">
            
           </div>
          
<devsite-search
    aria-expanded="false"
    aria-haspopup="listbox"
    enable-signin
    enable-search
    enable-suggestions
      enable-query-completion
    
    project-name="Google Business Profile APIs"
    tenant-name="Google Developers"
    project-scope="/my-business"
    url-scoped="https://developers.google.com/s/results/my-business"
    
    
    
    
    role="combobox">
  <form class="devsite-search-form" action="https://developers.google.com/s/results" method="GET">
    <div class="devsite-search-container">
      <div class="devsite-searchbox">
        <input
          aria-activedescendant=""
          aria-autocomplete="list"
          
          aria-label="Search"
          aria-haspopup="false"
          aria-multiline="false"
          aria-label="Search box"
          autocomplete="off"
          class="devsite-search-field devsite-search-query"
          name="q"
          
          placeholder="Search"
          role="searchbox"
          type="text"
          value=""
          >
        <div class="devsite-search-image material-icons" aria-hidden="true"></div>
      </div>
      <button type="button"
              search-open
              class="devsite-search-button devsite-header-icon-button button-flat material-icons"
              
              aria-label="Open search"></button>
    </div>
  </form>
  <button type="button"
          search-close
          class="devsite-search-button devsite-header-icon-button button-flat material-icons"
          
          aria-label="Close search"></button>
</devsite-search>

        </div>

        

        

        
<devsite-language-selector>
  <devsite-select class="devsite-language-selector-menu">
    
    <select aria-label="Select your language preference."
            class="devsite-language-selector-select"
            name="language"
            track-name="click"
            track-type="languageSelector">
    
      
      <option>Language</option>
    
    
      <option value="en"
              lang="en"
            >
        English
      </option>
    
      <option value="id"
              lang="id"
            >
        Bahasa Indonesia
      </option>
    
      <option value="de"
              lang="de"
            >
        Deutsch
      </option>
    
      <option value="es"
              lang="es"
            >
        Español
      </option>
    
      <option value="fr"
              lang="fr"
            >
        Français
      </option>
    
      <option value="pt_br"
              lang="pt_br"
            >
        Português – Brasil
      </option>
    
      <option value="ru"
              lang="ru"
            >
        Русский
      </option>
    
      <option value="zh_cn"
              lang="zh_cn"
            >
        中文 – 简体
      </option>
    
      <option value="ja"
              lang="ja"
            >
        日本語
      </option>
    
      <option value="ko"
              lang="ko"
            >
        한국어
      </option>
    
    </select>
  </devsite-select>
</devsite-language-selector>


        

        
          
          
          <devsite-user 
                        
                        
                          enable-profiles
                        
                        
                          fp-auth
                        
                        id="devsite-user">
            
              
              <span class="button devsite-top-button" aria-hidden="true" visually-hidden>Sign in</span>
            
        </devsite-user>
           
        
      </div>
    </div>
  </div>



  <div class="devsite-collapsible-section
    ">
    <div class="devsite-header-background">
      
        
      
      
        <div class="devsite-doc-set-nav-row">
          
          
            
            
  <devsite-tabs class="lower-tabs">

    <nav class="devsite-tabs-wrapper" aria-label="Lower tabs">
      
        
          <tab  >
            <a href="https://developers.google.com/my-business/content/overview"
   class="gc-analytics-event "
   track-type="nav"
   track-metadata-eventdetail="https://developers.google.com/my-business/content/overview"
   track-metadata-position="nav - guides"
   track-metadata-module="primary nav"
   
   
    
      data-category="Site-Wide Custom Events"
    
      data-label="Tab: Guides"
    
      track-name="guides"
    
  >
  Guides
</a>

          </tab>
        
      
        
          <tab  active>
            <a href="https://developers.google.com/my-business/ref_overview"
   class="gc-analytics-event "
   track-type="nav"
   track-metadata-eventdetail="https://developers.google.com/my-business/ref_overview"
   track-metadata-position="nav - reference"
   track-metadata-module="primary nav"
   aria-label="Reference, selected" 
   
    
      data-category="Site-Wide Custom Events"
    
      data-label="Tab: Reference"
    
      track-name="reference"
    
  >
  Reference
</a>

          </tab>
        
      
        
          <tab  >
            <a href="https://developers.google.com/my-business/samples"
   class="gc-analytics-event "
   track-type="nav"
   track-metadata-eventdetail="https://developers.google.com/my-business/samples"
   track-metadata-position="nav - samples"
   track-metadata-module="primary nav"
   
   
    
      data-category="Site-Wide Custom Events"
    
      data-label="Tab: Samples"
    
      track-name="samples"
    
  >
  Samples
</a>

          </tab>
        
      
        
          <tab  >
            <a href="https://developers.google.com/my-business/content/support"
   class="gc-analytics-event "
   track-type="nav"
   track-metadata-eventdetail="https://developers.google.com/my-business/content/support"
   track-metadata-position="nav - support"
   track-metadata-module="primary nav"
   
   
    
      data-category="Site-Wide Custom Events"
    
      data-label="Tab: Support"
    
      track-name="support"
    
  >
  Support
</a>

          </tab>
        
      
    </nav>

  </devsite-tabs>

          
          
        </div>
      
    </div>
  </div>

</div>



  

  
</devsite-header>
      <devsite-book-nav scrollbars >
        
          





















<div class="devsite-book-nav-filter
            ">
  <input type="text"
         placeholder="Filter"
         
         aria-label="Type to filter"
         role="searchbox">
  
  <span class="filter-clear-button hidden"
        data-title="Clear filter"
        aria-label="Clear filter"
        role="button"
        tabindex="0"></span>
</div>

<nav class="devsite-book-nav devsite-nav nocontent"
     aria-label="Side menu">
  <div class="devsite-mobile-header">
    <button type="button"
            id="devsite-close-nav"
            class="devsite-header-icon-button button-flat material-icons gc-analytics-event"
            data-category="Site-Wide Custom Events"
            data-label="Close navigation"
            aria-label="Close navigation">
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
    

</div>
  </div>

  <div class="devsite-book-nav-wrapper">
    <div class="devsite-mobile-nav-top">
      
        <ul class="devsite-nav-list">
          
            <li class="devsite-nav-item">
              
  
  <a href="/my-business/content/overview"
    
       class="devsite-nav-title gc-analytics-event
              
              devsite-nav-active"
    

    
      
        data-category="home"
      
        data-label="navTopMenu"
      
        track-name="home"
      
        data-action="tabClick"
      
    
     data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Home"
     track-type="globalNav"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav">
  
    <span class="devsite-nav-text" tooltip >
      Home
   </span>
    
  
  </a>
  

  
              
                <ul class="devsite-nav-responsive-tabs">
                  
                    
                    
                    
                    <li class="devsite-nav-item">
                      
  
  <a href="/my-business/content/overview"
    
       class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children
              "
    

    
      
        data-category="Site-Wide Custom Events"
      
        data-label="Tab: Guides"
      
        track-name="guides"
      
    
     data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Guides"
     track-type="globalNav"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav">
  
    <span class="devsite-nav-text" tooltip >
      Guides
   </span>
    
    <span class="devsite-nav-icon material-icons" data-icon="forward"
          >
    </span>
    
  
  </a>
  

  
                    </li>
                  
                    
                    
                    
                    <li class="devsite-nav-item">
                      
  
  <a href="/my-business/ref_overview"
    
       class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children
              devsite-nav-active"
    

    
      
        data-category="Site-Wide Custom Events"
      
        data-label="Tab: Reference"
      
        track-name="reference"
      
    
     data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Reference"
     track-type="globalNav"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav">
  
    <span class="devsite-nav-text" tooltip menu="_book">
      Reference
   </span>
    
    <span class="devsite-nav-icon material-icons" data-icon="forward"
          menu="_book">
    </span>
    
  
  </a>
  

  
                    </li>
                  
                    
                    
                    
                    <li class="devsite-nav-item">
                      
  
  <a href="/my-business/samples"
    
       class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children
              "
    

    
      
        data-category="Site-Wide Custom Events"
      
        data-label="Tab: Samples"
      
        track-name="samples"
      
    
     data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Samples"
     track-type="globalNav"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav">
  
    <span class="devsite-nav-text" tooltip >
      Samples
   </span>
    
    <span class="devsite-nav-icon material-icons" data-icon="forward"
          >
    </span>
    
  
  </a>
  

  
                    </li>
                  
                    
                    
                    
                    <li class="devsite-nav-item">
                      
  
  <a href="/my-business/content/support"
    
       class="devsite-nav-title gc-analytics-event
              devsite-nav-has-children
              "
    

    
      
        data-category="Site-Wide Custom Events"
      
        data-label="Tab: Support"
      
        track-name="support"
      
    
     data-category="Site-Wide Custom Events"
     data-label="Responsive Tab: Support"
     track-type="globalNav"
     track-metadata-eventDetail="globalMenu"
     track-metadata-position="nav">
  
    <span class="devsite-nav-text" tooltip >
      Support
   </span>
    
    <span class="devsite-nav-icon material-icons" data-icon="forward"
          >
    </span>
    
  
  </a>
  

  
                    </li>
                  
                </ul>
              
            </li>
          
          
          
        </ul>
      
    </div>
    
      <div class="devsite-mobile-nav-bottom" role="navigation">
        
          
          <ul class="devsite-nav-list" menu="_book">
            <li class="devsite-nav-item"><a href="/my-business/ref_overview"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Account Management</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1.1</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.admins</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.admins"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.admins/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.admins/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.admins/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.admins/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.invitations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.invitations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.invitations/accept"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>accept</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.invitations/decline"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>decline</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/accounts.invitations/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations/transfer"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>transfer</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.admins</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations.admins"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations.admins/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations.admins/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations.admins/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/accountmanagement/rest/v1/locations.admins/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li></ul></div></li></ul></div></li><li class="devsite-nav-item"><a href="/my-business/content/accountmanagement/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Business Calls</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/locations/getBusinesscallssettings"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getBusinesscallssettings</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/locations/updateBusinesscallssettings"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateBusinesscallssettings</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.businesscallsinsights</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/locations.businesscallsinsights"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/locations.businesscallsinsights/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/BusinessCallsSettings"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>BusinessCallsSettings</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businesscalls/rest/v1/ErrorCode"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorCode</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-new"><a href="/my-business/content/businesscalls/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Business Information</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/accounts.locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/accounts.locations/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/accounts.locations/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>attributes</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/attributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/attributes/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>categories</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/categories"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/categories/batchGet"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>batchGet</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/categories/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>chains</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/chains"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/chains/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/chains/search"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>search</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>googleLocations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/googleLocations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/googleLocations/search"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>search</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/associate"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>associate</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/clearLocationAssociation"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>clearLocationAssociation</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/getAttributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getAttributes</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/getGoogleUpdated"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getGoogleUpdated</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations/updateAttributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateAttributes</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.attributes</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations.attributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/locations.attributes/getGoogleUpdated"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getGoogleUpdated</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/AttributeValueType"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>AttributeValueType</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/Attributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Attributes</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/CategoryView"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>CategoryView</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/businessinformation/rest/v1/ErrorCode"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorCode</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-new"><a href="/my-business/content/businessinformation/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Lodging</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1.1</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/locations/getLodging"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getLodging</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/locations/updateLodging"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateLodging</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.lodging</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/locations.lodging"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/locations.lodging/getGoogleUpdated"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getGoogleUpdated</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/lodging/rest/v1/Lodging"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Lodging</span></a></li></ul></div></li><li class="devsite-nav-item"><a href="/my-business/content/lodging/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Notifications</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1.2</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest/v1/accounts"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest/v1/accounts/getNotificationSetting"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getNotificationSetting</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest/v1/accounts/updateNotificationSetting"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateNotificationSetting</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest/v1/ErrorCode"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorCode</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/notifications/rest/v1/NotificationSetting"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>NotificationSetting</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-new"><a href="/my-business/content/notifications/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Place Actions</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.placeActionLinks</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/locations.placeActionLinks/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>placeActionTypeMetadata</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/placeActionTypeMetadata"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/placeActionTypeMetadata/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/placeactions/rest/v1/ErrorCode"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorCode</span></a></li></ul></div></li><li class="devsite-nav-item"><a href="/my-business/content/placeactions/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Q&amp;A</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.questions</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions/deleteAnswers"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>deleteAnswers</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.questions.answers</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions.answers"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions.answers/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/qanda/rest/v1/locations.questions.answers/upsert"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>upsert</span></a></li></ul></div></li></ul></div></li><li class="devsite-nav-item"><a href="/my-business/content/qanda/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Verifications</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-new"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations/fetchVerificationOptions"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>fetchVerificationOptions</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations/getVoiceOfMerchantState"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getVoiceOfMerchantState</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations/verify"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>verify</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>locations.verifications</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations.verifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations.verifications/complete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>complete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/locations.verifications/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>verificationTokens</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/verificationTokens"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/verificationTokens/generate"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>generate</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/PostalAddress"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>PostalAddress</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/ServiceBusinessContext"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ServiceBusinessContext</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/Verification"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Verification</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/VerificationMethod"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>VerificationMethod</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/verifications/rest/v1/VerificationToken"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>VerificationToken</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-new"><a href="/my-business/content/verifications/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span><span class="devsite-nav-icon material-icons"
        data-icon="new"
        data-title="New!"
        aria-hidden="true"></span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v4.9</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/deleteNotifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>deleteNotifications</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/generateAccountNumber"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>generateAccountNumber</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/getNotifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getNotifications</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/listRecommendGoogleLocations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>listRecommendGoogleLocations</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/update"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>update</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts/updateNotifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateNotifications</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.admins</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.admins"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.admins/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.admins/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.admins/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.admins/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.invitations</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.invitations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.invitations/accept"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>accept</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.invitations/decline"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>decline</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.invitations/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/associate"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>associate</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/batchGet"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>batchGet</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/batchGetReviews"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>batchGetReviews</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/clearAssociation"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>clearAssociation</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/fetchVerificationOptions"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>fetchVerificationOptions</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/findMatches"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>findMatches</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/getFoodMenus"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getFoodMenus</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/getGoogleUpdated"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getGoogleUpdated</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/getHealthProviderAttributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getHealthProviderAttributes</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/getServiceList"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getServiceList</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/reportInsights"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>reportInsights</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/transfer"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>transfer</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/updateFoodMenus"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateFoodMenus</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations/updateHealthProviderAttributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateHealthProviderAttributes</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/updateServiceList"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateServiceList</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations/verify"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>verify</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.admins</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.admins"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.admins/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.admins/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.admins/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.admins/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.followers</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.followers"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.followers/getMetadata"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>getMetadata</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.insuranceNetworks</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.insuranceNetworks"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.insuranceNetworks/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.localPosts</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.localPosts/reportInsights"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>reportInsights</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.media</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media/startUpload"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>startUpload</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.media.customers</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media.customers"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media.customers/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.media.customers/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.questions</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions/create"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>create</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions/patch"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>patch</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.questions.answers</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions.answers"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions.answers/delete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>delete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions.answers/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.questions.answers/upsert"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>upsert</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.reviews</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.reviews"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.reviews/deleteReply"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>deleteReply</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.reviews/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.reviews/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/accounts.locations.reviews/updateReply"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>updateReply</span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>accounts.locations.verifications</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.verifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.verifications/complete"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>complete</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/accounts.locations.verifications/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>attributes</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/attributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/attributes/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>categories</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/categories"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/categories/batchGet"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>batchGet</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/categories/list"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>list</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>chains</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/chains"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/chains/get"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>get</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/chains/search"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>search</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-expandable
           devsite-nav-deprecated"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>googleLocations</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/googleLocations"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/googleLocations/report"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>report</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/googleLocations/search"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>search</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li></ul></div></li><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/AdminRole"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>AdminRole</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/AttributeValueType"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>AttributeValueType</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/Author"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Author</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/BasicMetricsRequest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>BasicMetricsRequest</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/CategoryView"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>CategoryView</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/Date"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Date</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/FoodMenus"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>FoodMenus</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/HealthProviderAttributes"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>HealthProviderAttributes</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/InsuranceNetwork"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>InsuranceNetwork</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/Metric"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Metric</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/MetricOption"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>MetricOption</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/MetricValue"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>MetricValue</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/Notifications"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Notifications</span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/PostalAddress"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>PostalAddress</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/ServiceBusinessContext"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ServiceBusinessContext</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item
           devsite-nav-deprecated"><a href="/my-business/reference/rest/v4/ServiceList"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ServiceList</span><span class="devsite-nav-icon material-icons"
        data-icon="deprecated"
        data-title="Deprecated"
        aria-hidden="true"></span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v4/TimeRange"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>TimeRange</span></a></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>v1 media</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>REST Resources</span>
      </div></li><li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>media</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item"><a href="/my-business/reference/rest/v1/media"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Overview</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/v1/media/upload"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>upload</span></a></li></ul></div></li></ul></div></li>

  <li class="devsite-nav-item
           devsite-nav-expandable"><div class="devsite-expandable-nav">
      <a class="devsite-nav-toggle" aria-hidden="true"></a><div class="devsite-nav-title devsite-nav-title-no-path" tabindex="0" role="button">
        <span class="devsite-nav-text" tooltip>Shared.Types</span>
      </div><ul class="devsite-nav-section"><li class="devsite-nav-item
           devsite-nav-heading"><div class="devsite-nav-title devsite-nav-title-no-path">
        <span class="devsite-nav-text" tooltip>Types</span>
      </div></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/ErrorCode"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorCode</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/ErrorDetail"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ErrorDetail</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/InternalError"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>InternalError</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/ValidationError"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>ValidationError</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/WriteRequest"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>WriteRequest</span></a></li><li class="devsite-nav-item"><a href="/my-business/reference/rest/Shared.Types/WriteResponse"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>WriteResponse</span></a></li></ul></div></li>

  <li class="devsite-nav-item"><a href="/my-business/content/change-log"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Change log</span></a></li>

  <li class="devsite-nav-item"><a href="/my-business/content/sunset-dates"
        class="devsite-nav-title"
      ><span class="devsite-nav-text" tooltip>Deprecation schedule</span></a></li>
          </ul>
        
        
          
    
  
        
        
          
    
  
    
  
    
  
    
  
        
      </div>
    
  </div>
</nav>
        
      </devsite-book-nav>
      <section id="gc-wrapper">
        <main role="main" class="devsite-main-content"
            has-book-nav
            has-sidebar>
          
          <div class="devsite-sidebar">
            <div class="devsite-sidebar-content">
              <devsite-toc class="devsite-nav"
                           role="navigation"
                           aria-label="On this page"
                           depth="2"
                           scrollbars
                ></devsite-toc>
              <devsite-recommendations-sidebar class="nocontent devsite-nav">
              </devsite-recommendations-sidebar>
            </div>
          </div>
          
          <devsite-content >
            
              

















<article class="devsite-article">
  
  
    <div class="devsite-banner devsite-banner-announcement"
         >
      <div class="devsite-banner-message">
        <div class="devsite-banner-message-text">
          The Q&A API is now launched! Migration work is required. Please see our <a href="https://developers.google.com/my-business/content/sunset-dates">deprecation schedule</a> for more information related to deprecated endpoints.<br> v1.1 of the Notifications API is now launched! Please see our <a href="https://developers.google.com/my-business/content/notifications/change-log">change log</a> for more information. You may also sign up for our <a href="https://docs.google.com/forms/d/e/1FAIpQLScsFulRVy5_Z969K0GBhpIhdYpN88I8TsMj229ViArhqod8Mw/viewform">mailing list</a> to receive updates.
        </div>
      </div>
    </div>
  
  

  <div class="devsite-article-meta nocontent" role="navigation">
    
    
    <ul class="devsite-breadcrumb-list"
  
    aria-label="Breadcrumb">
  
  <li class="devsite-breadcrumb-item
             ">
    
    
    
      
  <a href="https://developers.google.com/"
      
        class="devsite-breadcrumb-link gc-analytics-event"
      
        data-category="Site-Wide Custom Events"
      
        data-label="Breadcrumbs"
      
        data-value="1"
      
        track-type="globalNav"
      
        track-name="breadcrumb"
      
        track-metadata-position="1"
      
        track-metadata-eventdetail=""
      
    >
    
        Home
      
  </a>
  
    
  </li>
  
  <li class="devsite-breadcrumb-item
             ">
    
      
      <div class="devsite-breadcrumb-guillemet material-icons" aria-hidden="true"></div>
    
    
    
      
  <a href="https://developers.google.com/products"
      
        class="devsite-breadcrumb-link gc-analytics-event"
      
        data-category="Site-Wide Custom Events"
      
        data-label="Breadcrumbs"
      
        data-value="2"
      
        track-type="globalNav"
      
        track-name="breadcrumb"
      
        track-metadata-position="2"
      
        track-metadata-eventdetail=""
      
    >
    
        Products
      
  </a>
  
    
  </li>
  
  <li class="devsite-breadcrumb-item
             ">
    
      
      <div class="devsite-breadcrumb-guillemet material-icons" aria-hidden="true"></div>
    
    
    
      
  <a href="https://developers.google.com/my-business"
      
        class="devsite-breadcrumb-link gc-analytics-event"
      
        data-category="Site-Wide Custom Events"
      
        data-label="Breadcrumbs"
      
        data-value="3"
      
        track-type="globalNav"
      
        track-name="breadcrumb"
      
        track-metadata-position="3"
      
        track-metadata-eventdetail="Google Business Profile APIs"
      
    >
    
        Business Profile APIs
      
  </a>
  
    
  </li>
  
  <li class="devsite-breadcrumb-item
             ">
    
      
      <div class="devsite-breadcrumb-guillemet material-icons" aria-hidden="true"></div>
    
    
    
      
  <a href="https://developers.google.com/my-business/ref_overview"
      
        class="devsite-breadcrumb-link gc-analytics-event"
      
        data-category="Site-Wide Custom Events"
      
        data-label="Breadcrumbs"
      
        data-value="4"
      
        track-type="globalNav"
      
        track-name="breadcrumb"
      
        track-metadata-position="4"
      
        track-metadata-eventdetail=""
      
    >
    
        Reference
      
  </a>
  
    
  </li>
  
</ul>
    
      
    <devsite-thumb-rating position="header">
    </devsite-thumb-rating>
  
    
  </div>
  
  
    <h1 class="devsite-page-title">Account Management API</h1>
  
  <devsite-bookmark></devsite-bookmark>
  <devsite-toc class="devsite-nav"
               depth="2"
               devsite-toc-embedded
               >
  </devsite-toc>

  
  <devsite-recommendations-dropdown class="nocontent"></devsite-recommendations-dropdown>
  

  <div class="devsite-article-body clearfix
    ">

    
      




























































































   
</p>



<h2 id="change_log" data-text="Change log">Change log</h2>

<h3 id="v11" data-text="v1.1">v1.1</h3>

<h4 id="transfer_locations" data-text="Transfer Locations">Transfer Locations</h4>

<p>You can now use the Account Management API to transfer locations. The request body must include <code translate="no" dir="ltr">destinationAccount</code> (previously referred to as <code translate="no" dir="ltr">toAccount</code>.)  <a href="/my-business/reference/accountmanagement/rest/v1/locations/transfer">More info.</a></p>

<h3 id="v1" data-text="v1">v1</h3>

<h4 id="api_access" data-text="API Access">API Access</h4>

<p>The Account Management API will need to be enabled from the <a href="https://console.developers.google.com/apis/library/mybusinessaccountmanagement.googleapis.com">GCP Console.</a> The OAuth scope remains the same.</p>

<h4 id="endpoint_url" data-text="Endpoint URL">Endpoint URL</h4>

<p>The Account Management API is accessible at <code translate="no" dir="ltr">https://mybusinessaccountmanagement.googleapis.com/v1/accounts/{accountId}</code> instead of <code translate="no" dir="ltr">https://mybusiness.googleapis.com/v4/accounts/{accountId}</code></p>

<h4 id="listinvitations_filtering" data-text="ListInvitations filtering">ListInvitations filtering</h4>

<p>Previously, invitations could be filtered using the <code translate="no" dir="ltr">target_type</code> URL parameter. In the Account Management API, this has been replaced with a <code translate="no" dir="ltr">filter</code> parameter. Clients will be able to filter using values like <code translate="no" dir="ltr">?filter=target_type=ACCOUNT_ONLY</code>.</p>

<h4 id="primary_owner" data-text="Primary Owner">Primary Owner</h4>

<p>`PrimaryOwner&#39; has moved to the POST body in the <a href="/my-business/content/accountmanagement/my-business/preview/reference/accountmanagement/rest/v1/accounts/create">accounts.create</a> method. Previously this was a query parameter.</p>

<h4 id="generateaccountnumber_functionality_has_been_deprecated" data-text="GenerateAccountNumber functionality has been deprecated."><code translate="no" dir="ltr">GenerateAccountNumber</code> functionality has been deprecated.</h4>

<h4 id="listrecommendgooglelocations_functionality_has_been_deprecated" data-text="ListRecommendGoogleLocations functionality has been deprecated."><code translate="no" dir="ltr">ListRecommendGoogleLocations</code> functionality has been deprecated.</h4>

<h4 id="all_updates_now_require_a_field_mask" data-text="All updates now require a field mask">All updates now require a field mask</h4>

<p>You can no longer make update/patch calls without the updateMask parameter in the URL.</p>

<h4 id="updated_account_role_and_admin_role_names" data-text="Updated account role and admin role names">Updated account role and admin role names</h4>

<p>Account/Admin roles names have changed as follows:</p>

<table>
<thead>
<tr>
<th>Previous name</th>
<th>Updated name</th>
</tr>
</thead>

<tbody>
<tr>
<td>OWNER</td>
<td>PRIMARY_OWNER</td>
</tr>
<tr>
<td>CO_OWNER</td>
<td>OWNER</td>
</tr>
<tr>
<td>COMMUNITY_MANAGER</td>
<td>SITE_MANAGER</td>
</tr>
</tbody>
</table>

<h4 id="organizationinfopostal_address_is_renamed_to_organizationinfoaddress" data-text="OrganizationInfo.postal_address is renamed to OrganizationInfo.address">OrganizationInfo.postal_address is renamed to OrganizationInfo.address</h4>

    

    
  </div>

  

  
    
      <devsite-recommendations display="in-page" hidden yield>
      </devsite-recommendations>
    
    
      
    <devsite-thumb-rating position="footer">
    </devsite-thumb-rating>
  
       
    
    
      <devsite-recommendations id="recommendations-link" yield></devsite-recommendations>
    
  

  
  
