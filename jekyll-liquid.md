---
title: Liquid objects tags and filters
---
layout: default
title: The Hello World Page
---
---
{% include cookie-warning.html %}
<h1> {{page.titlt}} </h1>


Liquid lets you do a lot!


{{ page.title | upcase }}

{{page.title | remove: "and"}}

{{ 'logo' | append: '.jpg' }}

{{"I wish I was an Oscar Myers winter." | truncatewords: 4 }}

{% unless page.title
