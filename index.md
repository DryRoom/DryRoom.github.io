---
layout: default
title: Home
---

<div class="posts">
  {% for post in site.posts %}
    <div class="post">
      <h1 class="post-title">
        <a href="{{ post.url }}">
          {{ post.title }}
        </a>
      </h1>
      <span class="post-date">{{ post.date | date_to_string }}</span>
      <p>Welcome to my Blog. I know I'm too late to enter the Blog Culture amidst the era of social media but you know what they say, "Better Late Than Never!". Click the title above to read my first official update.</p>
    </div>
  {% endfor %}
</div>
