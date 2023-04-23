---
layout: default
title:  "Resources"
---

<h1>Resources</h1>

<div>
<ul class="resourcelist">
{% for resource in site.static_files %}
{% if resource.path contains 'assets/resources/' %}
<div>
<li>
<a target="_blank" href="{{ resource.path }}" alt="Resource file">{{ resource.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

