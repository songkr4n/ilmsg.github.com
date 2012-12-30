---
# layout: profile
title: "Eak Netpanya"
description: "Programmer PHP, CodeIgniter, Java, Javascript, jQuery, Node.js, C#, Asp.net, App Facebook Developer"
---
{% include JB/setup %}

<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml"
xmlns:og="http://ogp.me/ns#"
xmlns:fb="http://www.facebook.com/2008/fbml"
lang="th">
	<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# profile: http://ogp.me/ns/profile#">
	<meta property="fb:app_id"               content="384117654995313"> 
	<meta property="og:type"                 content="profile"> 
	<meta property="og:url"                  content="http://blog.ilmsg.com{{ page.url }}">
	<meta property="og:image" 				content="https://raw.github.com/ilmsg/ilmsg.github.com/master/_upload/eak.netpanya.jpg">
	<meta property="og:title"                content="Eak Netpanya">
	<meta property="og:description"          content="Programmer PHP, CodeIgniter, Java, Javascript, jQuery, Node.js, C#, Asp.net, App Facebook Developer">
	<meta property="profile:first_name"      content="Eak">
	<meta property="profile:last_name"       content="Netpanya">
	<meta property="profile:username"        content="ilmsg">
	<meta property="profile:gender"          content="male">
	<meta property="fb:profile_id"           content="100003564668438">
	<meta charset="utf-8">
	<title>{{ page.title }}</title>
    {% if page.description %}<meta name="description" content="{{ page.description }}">{% endif %}
    <meta name="author" content="{{ site.author.name }}">

    <!-- Le HTML5 shim, for IE6-8 support of HTML elements -->
    <!--[if lt IE 9]>
      <script src="http://html5shim.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->

    <!-- Le styles -->
    <link href="{{ ASSET_PATH }}/bootstrap/css/bootstrap.min.css" rel="stylesheet">
    <link href="{{ ASSET_PATH }}/css/style.css?body=1" rel="stylesheet" type="text/css" media="all">

    <!-- Le fav and touch icons -->
  <!-- Update these with your own images
    <link rel="shortcut icon" href="images/favicon.ico">
    <link rel="apple-touch-icon" href="images/apple-touch-icon.png">
    <link rel="apple-touch-icon" sizes="72x72" href="images/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="114x114" href="images/apple-touch-icon-114x114.png">
  -->
  </head>

  <body>

    <div class="navbar">
      <div class="navbar-inner">
        <div class="container">
          <a class="brand" href="{{ HOME_PATH }}">{{ site.title }}</a>
          <ul class="nav">
            {% assign pages_list = site.pages %}
            {% assign group = 'navigation' %}
            {% include JB/pages_list %}
          </ul>
        </div>
      </div>
    </div>

    <div class="container">

      <div class="content">
        {{ content }}
      </div>

      <footer>
        <p>&copy; {{ site.author.name }} 2012 
          ก็ได้ <a href="http://jekyllbootstrap.com" target="_blank" title="The Definitive Jekyll Blogging Framework">Jekyll Bootstrap</a>
          กับ <a href="http://twitter.github.com/bootstrap/" target="_blank">Twitter Bootstrap</a> ตี่มาจวยกันแป๋ง blog นี้ ขอบคุณนักๆเน้อ
        </p>
      </footer>

    </div> <!-- /container -->

    {% include JB/analytics %}
  </body>
</html>