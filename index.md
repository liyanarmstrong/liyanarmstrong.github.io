---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Stay hungry,stay foolish. --Steve Jobs

Make it better everyday...

## The Plans for This Week

This week to be accomplished:

    1.Reading "Three Body" 

    2.Beautify the Blog

    3.continue learning ruby,python,linux ...
    
Just like the worklog,it is a good way to summarize by recording   

## Program exercise

If you want to be a developer,you'd better exercise three years ago, or from now on

    1.Python



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

