---
layout: page
title: Welcome to SteelCloud!
tagline: The Pittsburgh-area cloud application developers' user group
---
{% include JB/setup %}

## Who We Are

SteelCloud is a user group / meetup for Pittsburgh-area cloud application developers.  We get together to discuss technologies, architecture, patterns and techniques of interest to developers working on large-scale, distributed applications.

We try to meet monthly - either to hear engaging speakers present topical information, or to open the floor to roundtable discussion of what's on our collective mind.

## Where to Find Us

SteelCloud generally meets at the Confluence building on Pittsburgh's North Shore:

#### 600 River Ave
#### Pittsburgh, PA  15212
#### ([map](http://goo.gl/maps/Survl))

You can also checkout our [meetup group](http://www.meetup.com/steelcloud) to check for upcoming events.

## How to Join

Email us at [join at steelcloud dot org](mailto:join@steelcloud.org), or sign up on the [meetup group](http://www.meetup.com/steelcloud).

## What's Been Happening Lately

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
