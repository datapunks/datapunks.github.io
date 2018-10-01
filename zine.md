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

Ready to revolutionize your data?

<form class="w3-container w3-card-4 spacer" style="background: #444851" method="POST" action="https://formspree.io/david@datapunks.ca">
  <h2 style="text-transform: uppercase">See it in action</h2>
  <p>      
  <label>Name</label>
  <input class="w3-input w3-border-0" type="text" name="Name"></p>
  <p>      
  <label>Email</label>
  <input class="w3-input w3-border-0" type="text" name="Email"></p>
  <p>      
  <label>Organization website</label>
  <input class="w3-input w3-border-0" type="text" name="Organization"></p>
  <p>      
  <label>Message</label>
  <textarea class="w3-input w3-border-0" type="text" name="Message"></textarea>
  <div id="submit-button">
  <button class="w3-btn spacer-small" id="submit-button" style="background:#23eeec; text-transform: uppercase; font-family:'roboto', sans-serif;">Submit</button>
  </div>
