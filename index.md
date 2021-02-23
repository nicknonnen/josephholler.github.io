---
title: Main Page
layout: default
---

# Joseph Holler's Open Source GIS Porfolio
Hi, I am Joseph Holler and I am super enthusiasic about teaching the second round of Open Source GIScience.
I really shouldn't put information like "second round" in this video, because it'll be super lame when I try to re-use the video next year.

- [Gravity Model of Spatial Interaction](gravity/gravity.md)
- item number two

1. first thing
1. second thing
1. third thing
1111. fourth thing

The course website is found [here](https://gis4dev.github.io).

Thanks, have a great rest of your day. Because Vermont.

_HOWEVER_ remember that sometimes GitHub takes a few minutes, maybe even ten whole minutes, to render new changes to your website.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

updated {{ date }}
