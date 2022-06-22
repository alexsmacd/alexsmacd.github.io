# WordPress Plugins

{% for plugin in site.plugins %}
  <h4>{{ plugin.name }}</h4>
  <a href="{{ plugin.link }}" target="_blank"><img src="{{ plugin.thumb }}" /></a>
{% endfor %}
