---
layout: default
title: Home
---
# Project Updates
Project log. I will post updates on the progress being made.
## Recent Entries
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.date | date: "%B %d, %Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
---
