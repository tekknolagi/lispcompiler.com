---
---
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="alternate" type="application/rss+xml" title="Feed" href="{{ site.url }}/feed.xml" />
  <title>{{ page.title }}</title>
  <style type="text/css">
  body {
    margin: 40px auto;
    max-width: 650px;
    line-height: 1.6;
    font-size: 18px;
    padding: 0 10px
    font-family: serif;
  }
  
  h1,
  h2,
  h3 {
    line-height: 1.2
  }
  </style>
</head>

<body>
  <header>
    <h1>{{ page.title }}</h1>
  </header>
  <div class="pagecontents">
  {{ content }}
  </div>
  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=UA-26440738-6"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'UA-26440738-6');
  </script>
</body>

</html>
