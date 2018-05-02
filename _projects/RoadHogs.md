---
layout: project
title:  "Roadhogs"
# date:   2016-02-22 15:45:50
# category: Goals
# tags: Goals
---
# Roadhogs Motorcycle club - RoadHogs.com


<div class="project_sample">
Roadhogs Motorcycle club wanted a custom wordpress theme to replace their previous website.They used the site do relay upcoming events as well as recap previous events with details and photos. They also wanted it to have restricted access to only current members.
</div>
<div class="project_sample">
{% for image in site.static_files %}
{% if image.path contains 'img/Roadhogs/' %}
<img src="{{ site.baseurl }}{{ image.path }}" alt="image" class="project_image"/>
{% endif %}
{% endfor %}
</div>


