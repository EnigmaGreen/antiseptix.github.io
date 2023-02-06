---
layout: defaultpro
type: 
typepro: navleft
sort: 1
title: Products
css: navspecialleft
thumbnail: https://images.unsplash.com/photo-1615561916422-7014e1078997?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80
breadcrumbs: false
---
# {{page.title}}

<div class="container py-3 g-sm-0 subcardssectionsscaledown">
    <div class="row">
        {% assign sorted_applications = site.pages | where:"typepro", "Products" | sort: "sort" %}
        {% for p in sorted_applications %}
            <div class="col-12 col-sm-6 col-md-4 py-3">
                <div class="card">
                    <a href="{{ site.baseurl }}{{ p.url }}" class="text-decoration-none fw-bold text-dark">
                        <img src="{{ p.thumbnail }}" class="card-img-top" alt="...">
                        <div class="card-body text-center">
                        <p class="card-text">{{p.title}}</p>
                        </div>
                    </a>
                  </div>
        </div>
        {% endfor %}
    </div>
    
</div>