---
layout: default
title:  "Reports"
---

<h1>Projects</h1>

<div>
<ul class="projectlist">
{% for pdf in site.static_files %}
{% if pdf.path contains 'assets/projects/' %}
<div>
<li>
<a target="_blank" href="{{ pdf.path }}" alt="project file">{{ pdf.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

