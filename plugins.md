---
title: Plugins
permalink: /plugins/
---

<ul>
{% for plugin in site.plugins %}
<li>
  {{ plugin.name }} <a href="{{ plugin.link }}" target="_blank">#</a>
{% endfor %}
</ul>
