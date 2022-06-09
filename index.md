# Hello, I'm Alex MacDonald

* This is a list item
* This is a list item   

## Items

{% for item in site.items %}
  <h4>{{ item.name }}</h4>
  <a href="{{ item.url }}" target="_blank"><img src="{{ item.thumb }}" /></a>
{% endfor %}