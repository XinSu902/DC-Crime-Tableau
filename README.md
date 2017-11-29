## hello-world
something new
   <title>{% if page.title %}{{ page.title | escape }}{% else %}{{ site.title | escape }}{% endif %}</title>
   <meta name="description" content="{% if page.excerpt %}{{ page.excerpt | strip_html | strip_newlines | truncate: 160 }}{% else %}{{ site.description }}{% endif %}">
 
-  <link rel="shortcut icon" type="image/png" href="{{ site.baseurl }}/assets/logo.png">
+  <link rel="shortcut icon" type="image/png" href="{{ site.baseurl }}/img/logo.png">
 
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
   <link rel="stylesheet" href="{{ site.baseurl }}/css/main.css">
