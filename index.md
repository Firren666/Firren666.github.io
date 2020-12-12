---
post_limit: 5
---

## Rubrik

Stycke 1

### Latest posts

{% for post in site.posts %}

	<a href="{{ post.url }}">{{ post.title }}</a>
	{{ post.excerpt }}
	
{% endfor %}

### All posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
