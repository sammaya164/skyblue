---
layout: default
---
<ul>
	{% for post in site.posts %}
	<li><a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}"><img src="{{ site.baseurl }}/assets/img/file.ico" title="{{ post.title }}" />{{ post.title }}</a></li>
	{% endfor %}
</ul>
