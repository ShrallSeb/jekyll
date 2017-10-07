---
title: Page d'accueil
description: Ma description
author: Moi-meyme
---

# jekyll-Accueil

Paris Web 2017

## Gros patapouf

Texte *italique* _italique_ **gras** __gras__ 

Et voici **du texte en gras _italique_ mon gros pépère !**

{{ site.title }}
<h1>{{ page.title }}</h1>

<ul>
{% for page in site.html_pages %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>

Yo

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
