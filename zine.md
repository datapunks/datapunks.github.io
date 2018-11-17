---
layout: page
title: Zine. Maga-free
---

<ul>
  {% for post in site.posts limit:1 %}
    <h5>Latest Post</h5>
    <h3>{{ post.title }}</h3>
    <time datetime="{{ content.date | date_to_xmlschema }}" class="post-date">{{ post.date | date_to_string }}</time>
    {{ post.content }}
  {% endfor %}
</ul>

<br>
More articles:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
