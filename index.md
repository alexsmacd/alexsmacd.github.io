# Hello, I'm Alex MacDonald

## Items

{% for item in site.items %}
  <h4>{{ item.name }}</h4>
  <a href="{{ item.link }}" target="_blank"><img src="{{ item.thumb }}" /></a>
{% endfor %}
