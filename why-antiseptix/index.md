---
layout: default
type: navleft
sort: 2
title: Why AntiSeptix?
css: d-none d-sm-block
thumbnail: https://images.unsplash.com/photo-1626202373152-8db1760c8f61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1180&q=80
breadcrumbs: false
---
# {{page.title}}

## Organic

AntiSeptix is completely organic advanced antiseptic and disinfectant that kills 99.99% of bacteria and viruses, including Coronavirus.

- No Alcohol
- Works in 10 seconds
- Organis
- Moisturises
- Vegan
- Made in UK

## Natural

AntiSeptix replicates natural particles created by our own immune system in order to eradicate invasive organisms and fight injections.

## Antiseptic and antibacterial

AntiSeptix is a natural antiseptic and antibacterial liquid solution.


<div class="container py-3 g-sm-0 subcardssections">
    <div class="row">
        {% assign sorted_applications = site.pages | where:"type", "why-antiseptix" | sort: "sort" %}
        {% for p in sorted_applications %}
            <div class="col-12 col-sm-6 col-md-4 py-3">
                <div class="card">
                    <a old-href="{{ site.baseurl }}{{ p.url }}" class="text-decoration-none fw-bold text-dark">
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

## As well as the above, AntiSeptix is also:

- Highly-effective virucidal, antibacterial, sporicidal and fungicidal
- Completely organic
- Uses natural materials in a special manufacturing process
- Stable solution with a long shelf life
- Completely non-toxic - safe for adults, children and pets