---
layout: default
title: News
---

<!-- This page renders automatically from the _news/ collection --
     you don't edit this file to add an entry. To add a news item,
     create a new file in _news/ (see the README in that folder
     for the format) and it will appear here automatically, newest
     first, and on the homepage teaser if it's among the 3 most
     recent. -->

{% assign all_news = site.news | sort: 'date' | reverse %}
{% for entry in all_news %}
  <div class="news-entry">
    <div class="thumb">
      {% if entry.image %}
        <img src="{{ entry.image | relative_url }}" alt="">
      {% else %}
        <img src="{{ '/assets/images/news/placeholder.jpg' | relative_url }}" alt="">
      {% endif %}
    </div>
    <div>
      <div class="meta">{{ entry.date | date: "%B %Y" }}{% if entry.category %} &middot; {{ entry.category }}{% endif %}</div>
      <div class="summary">{{ entry.content | markdownify }}</div>
    </div>
  </div>
{% endfor %}
