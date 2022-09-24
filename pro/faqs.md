---
layout: defaultpro
typepro: navright
sort: 3
title: FAQs
css: d-none d-sm-block
thumbnail: https://images.unsplash.com/photo-1626202373152-8db1760c8f61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1180&q=80
breadcrumbs: false
---
# {{page.title}}

## Is Antiseptix Bathroom Disinfectant suitable to use on all my bathroom surfaces?

Antiseptix Bathroom Disinfectant Spray can be used on all bathroom surfaces except for marble, brass, copper, unfinished wood, carpet, fabric and unwaxed vinyl.

## Will Antiseptix Bathroom Disinfectant, disinfect the invisible bacteria in my bathroom?

YES! Antiseptix will kill 99.9% of bacteria*. Soap scum and watermarks are also removed.

## Is Antiseptix Bathroom Disinfectant suitable to use in households with children and pets?

YES! Antiseptix is chemical free, Alcohol free and is 100% natural as well and being non- toxic. Please ensure the product remains out of a child’s reach. 

<div class="container py-3 g-sm-0">
    <div class="row">
        {% assign sorted_applications = site.pages | where:"type", "faqs" | sort: "sort" %}
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