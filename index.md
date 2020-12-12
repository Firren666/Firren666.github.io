---
post_limit: 5
---

## Oh hello!

{% for post in site.posts %}
<div>
	<a href="{{ post.url }}">{{ post.title }}</a>
	{{ post.content }}
</div>
{% endfor %}

[Articles](/archive)


