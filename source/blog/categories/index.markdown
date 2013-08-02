---
layout: page
title: "Categories"
date: 2013-07-28 23:11
comments: true
sharing: false
footer: true
---
<ul>
{% for item in site.categories %}
    <li><a href="/blog/categories/{{ item[0] }}/">{{ item[0] | capitalize }}</a> [ {{ item[1].size }} ]</li>
{% endfor %}
</ul>
