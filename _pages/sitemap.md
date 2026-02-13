---
layout: single
title: "Sitemap"
permalink: /sitemap/
---
<h1>Sitemap</h1>
<p>A list of all the posts and pages found on the site. For robots, an <a href="{{ "/sitemap.xml" | relative_url }}">XML version</a> is also available.</p>

<h2>Pages</h2>
<ul>
{% for page in site.pages %}
  {% if page.title and page.sitemap != false and page.url != "/404.html" and page.url != "/sitemap/" %}
    <li><a href="{{ page.url | relative_url }}">{{ page.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>

<h2>Posts</h2>
<ul>
{% for post in site.posts %}
  {% if post.sitemap != false %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> ({{ post.date | date: "%Y-%m-%d" }})</li>
  {% endif %}
{% endfor %}
</ul>

{% assign ignored_collections = "posts" | split: "," %}
{% for collection in site.collections %}
  {% unless ignored_collections contains collection.label or collection.output == false %}
    {% assign collection_docs = collection.docs | where_exp: "doc", "doc.sitemap != false" %}
    {% if collection_docs.size > 0 %}
      <h2>{{ collection.label | capitalize }}</h2>
      <ul>
      {% for doc in collection_docs %}
        <li><a href="{{ doc.url | relative_url }}">{{ doc.title }}</a></li>
      {% endfor %}
      </ul>
    {% endif %}
  {% endunless %}
{% endfor %}
