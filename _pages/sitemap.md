---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there, an [XML version]({{ base_path }}/sitemap.xml) is also available.

<h2>Pages</h2>
<ul>
{% for page in site.pages %}
  {% if page.title and page.sitemap != false and page.url != "/404.html" and page.url != "/sitemap/" %}
    <li>
      <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
    </li>
  {% endif %}
{% endfor %}
</ul>

<h2>Posts</h2>
<ul>
{% for post in site.posts %}
  {% if post.sitemap != false %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endif %}
{% endfor %}
</ul>

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    <h2>{{ collection.label | capitalize }}</h2>
    <ul>
    {% for doc in collection.docs %}
      {% if doc.sitemap != false %}
        <li>
          <a href="{{ doc.url | relative_url }}">{{ doc.title }}</a>
        </li>
      {% endif %}
    {% endfor %}
    </ul>
  {% endunless %}
{% endfor %}
