---
layout: default
type: applications
sort: 1
title: Household
thumbnail: https://images.unsplash.com/photo-1556911073-38141963c9e0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1770&q=80
---
# {{page.title}}

fasdasd

## asdasdasdasd

- asdasdasdasd
- asdasdasdasdad


asdasdasdasd
asdasdasdasd



{% assign sorted_pages = site.pages | where:"type", "household" | sort: "sort" %}
{% for p in sorted_pages %}
{% include button.html innerpage=p %}
{% endfor %}