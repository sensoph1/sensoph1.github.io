---
layout: blog
title: Blog
order: 2
---

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<div class="home">


  <div class="post-list">
    {% for post in site.posts %}
     <div class="post-wrapper">
      <div class="content-wrapper">
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
         {{ post.content }}

      <div class="labels">
       <p class="date">{{ post.date | date: "%b %-d, %Y" }}</p>
       <p class="category"> {{ post.tags }} </p>
    </div>
  </div>
</div>

    {% endfor %}
  </div>

  <!-- <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p> -->

</div>

