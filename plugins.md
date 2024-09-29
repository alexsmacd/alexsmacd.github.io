---
title: Plugins
permalink: /plugins/
---

<div id="content" class="grid-container">
{% for plugin in site.plugins %}
<div class="grid-item">
<a href="{{ plugin.link }}" target="_blank"><img src="{{ plugin.icon }}"></a>
<h3><a href="{{ plugin.link }}" target="_blank">{{ plugin.name }}</a></h3>
</div>
{% endfor %}
</div>
