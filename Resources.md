---
layout: default
title:  "Resources"
---

<h1>Resources</h1>

<div>
<h2>Text Books</h2>
<ul class="projectlist">
{% for resource in site.static_files %}
{% if resource.path contains 'assets/resources/Textbooks' %}
<div>
<li>
<a target="_blank" href="{{ resource.path }}" alt="Resource file">{{ resource.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

<div>
<h2>References</h2>
<ul class="projectlist">
{% for resource in site.static_files %}
{% if resource.path contains 'assets/resources/References' %}
<div>
<li>
<a target="_blank" href="{{ resource.path }}" alt="Resource file">{{ resource.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

<div>
<h2>Papers</h2>
<ul class="projectlist">
{% for resource in site.static_files %}
{% if resource.path contains 'assets/resources/Papers' %}
<div>
<li>
<a target="_blank" href="{{ resource.path }}" alt="Resource file">{{ resource.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

