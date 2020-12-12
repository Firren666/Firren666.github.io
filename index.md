---
post_limit: 5
---


{% for post in site.posts %}
<div>
	{{ post.excerpt }}
	<a href="{{ post.url }}">read more</a>
</div>
{% endfor %}

[Archive](/archive)


