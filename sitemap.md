---
title: Sitemap
layout: default
permalink: sitemap
---
<ul class="iconlist">
{% for page in site.pages %}
<li><i class="icon-folder-close"></i> <a href="{{page.url}}">{{page.title}}</a></li>
{% endfor %}
</ul>