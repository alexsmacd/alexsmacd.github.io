---
title: Plugins
permalink: /plugins/
---

<ul>
{% for plugin in site.plugins %}
<li>
  <h3>{{ plugin.name }} <a href="{{ plugin.link }}" target="_blank">#</a></h3>
</li>
{% endfor %}
</ul>
