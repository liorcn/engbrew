---
layout: page
permalink: "/blog/"
title: "בלוג"
---

<div class="container px-4 px-lg-5">
  <div class="row gx-4 gx-lg-5 justify-content-center">
      <div class="col-md-10 col-lg-8 col-xl-7">
          <!-- Post preview-->
        <h3>פוסטים אחרונים</h3>

        {% for post in site.posts limit: 5 %}
        <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
        {% endfor %}

      </div>
  </div>
</div>