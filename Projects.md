---
layout: default
title:  "Projects"
---

<h1>Projects</h1>

<div>
<ul class="projectlist">
{% for pdf in site.static_files %}
{% if pdf.path contains 'assets/projects/' %}
<div>
<li>
<a href="{{ pdf.path }}" alt="project file">{{ pdf.name }}</a>
</li>
</div>
{% endif %}
{% endfor %}
</ul>
</div>

