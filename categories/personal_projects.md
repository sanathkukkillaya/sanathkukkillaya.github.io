---
layout: page
title: Personal Projects
permalink: /portfolio/categories/personal_projects/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.personal_projects %}
 <li class="category-posts"><span>{{ post.date | date: "%b %Y" }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>