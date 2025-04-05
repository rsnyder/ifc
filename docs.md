---
layout: default
title: Docs
category: component
---

## Getting Started

- [GitHub]({{site.baseurl}}/docs/github)
- [Jekyll]({{site.baseurl}}/docs/jekyll)
- [Markdown]({{site.baseurl}}/docs/markdown)

## Juncture Iframe Components
<ul>
{% assign docs = site.docs | where: "category", "component" %}
{% for doc in docs %}
  {% if page.url == doc.url %}
    <li class="active" data-path="{{site.baseurl}}{{doc.url}}">
  {% else %}
     <li data-path="{{site.baseurl}}{{doc.url}}">
  {% endif %}
    <a href="{{site.baseurl}}{{doc.url}}">
      {{ doc.title | escape }}
    </a>
  </li>
{% endfor %}
</ul>

## HowTo Guides
<ul>
{% assign docs = site.docs | where: "category", "howto" %}
{% for doc in docs %}
  {% if page.url == doc.url %}
    <li class="active" data-path="{{site.baseurl}}{{doc.url}}">
  {% else %}
     <li data-path="{{site.baseurl}}{{doc.url}}">
  {% endif %}
    <a href="{{site.baseurl}}{{doc.url}}">
      {{ doc.title | escape }}
    </a>
  </li>
{% endfor %}
</ul>