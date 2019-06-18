# The homepage

This is the homepage

{% for post in site.posts %}
  <a href = {{post.url}}>{{post.title}}</a>
{% endfor %}
