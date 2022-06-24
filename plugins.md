---
title: Plugins
permalink: /plugins/
---

<ul>
{% for plugin in site.plugins %}
<li>
  <h3>{{ plugin.name }} <a href="{{ plugin.link }}" target="_blank"><img src="assets/link.png"></a></h3>
</li>
{% endfor %}
</ul>
