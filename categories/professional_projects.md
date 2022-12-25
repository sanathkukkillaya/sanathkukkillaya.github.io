---
layout: page
title: Professional Projects
permalink: /portfolio/categories/professional_projects/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.professional_projects %}
 <li class="category-posts"><span>{{ post.date | date: "%b %Y" }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>