---
post_limit: 5
---


{% for post in site.posts %}
<article>
	{{ post.excerpt }}
	<br>
	<a href="{{ post.url }}">read more</a>
</article>
{% endfor %}

[Archive](/archive)


