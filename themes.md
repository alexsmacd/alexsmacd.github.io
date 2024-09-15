---
title: Themes
permalink: /themes/
---

<div id="content" class="grid-container">
{% for theme in site.themes %}
<div class="grid-item">
<a href="{{ theme.link }}" target="_blank"><img src="{{ theme.thumb }}"></a>
<h3><a href="{{ theme.link }}" target="_blank">{{ theme.name }}</a></h3>
</div>
{% endfor %}
</div>
