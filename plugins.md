---
title: Plugins
permalink: /plugins/
---

{% for plugin in site.plugins %}
<div>
  <a href="{{ plugin.link }}" target="_blank"><img src="{{ plugin.thumb }}" style="float:left; margin-right:20px;" />
  <h4>{{ plugin.name }}</h4>
  </a>
</div>
{% endfor %}
