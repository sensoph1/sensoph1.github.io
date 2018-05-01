---
# layout: projects
title: projects
---
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div class="home">


  <div class="post-list">
    {% for item in site.projects %}
        <h2>{{ item.title }}</h2>
        <p>{{ item.description }}</p>
        <p><a href="{{ item.url }}">{{ item.title }}</a></p>
    {% endfor %}

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

