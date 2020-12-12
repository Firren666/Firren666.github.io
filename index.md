---
post_limit: 5
---

## Rubrik

Stycke 1

### Latest posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.content }}
    </li>
  {% endfor %}
</ul>

### All posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
