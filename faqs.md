---
layout: defaultnosplash
type: navright
sort: 3
title: FAQs
css: d-none d-sm-block
thumbnail: https://images.unsplash.com/photo-1626202373152-8db1760c8f61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1180&q=80
breadcrumbs: false
---
# {{page.title}}

## Is Antiseptix Disinfectant suitable to use on all my bathroom surfaces?

Antiseptix Disinfectant Spray can be used on all bathroom surfaces except for marble, brass, copper, unfinished wood, carpet, fabric and unwaxed vinyl.

## Will Antiseptix Disinfectant disinfect the invisible bacteria in my bathroom?

YES! Antiseptix will kill 99.9% of bacteria*. Soap scum and watermarks are also removed.

## Is Antiseptix Disinfectant suitable to use in households with children and pets?

YES! Antiseptix is chemical free, Alcohol free and is 100% natural as well and being non- toxic. Please ensure the product remains out of a child’s reach.

## Do I need to wear gloves using Antiseptix Disinfectant?

NO! Antiseptix Disinfectant is non-toxic and chemical free. It is safe to use without gloves. 

## How long can I use Antiseptic Disinfectant for after opening?

We recommend that once opened Antiseptix Disinfectant should be used within 12 months, but we are sure you will be using it way sooner. 

## Does Antiseptix Disinfectant kill Covid-19? 

Yes.  All Antiseptix products have demonstrated effectiveness against the Covid-19 virus (SARS-CoV-2) when used in accordance with the directions for use. 

## Is it safe to use Antiseptix Disinfectant on wooden floors? 

Antiseptix Disinfectant is suitable to be used on sealed wooden floors, Tiles, Hardwood, Laminated flooring, Concrete and Hard Floors.

## Is Antiseptix Disinfectant suitable to use in households with children and pets?

YES! Antiseptix is chemical free, Alcohol free and is 100% natural as well and being non- toxic. Please ensure the product remains out of a child’s reach.

## Is Antiseptix Multi Surface Disinfectant suitable for me to use on my worktop?

While this can be used on a variety of worktop surfaces, for more detail, refer to the product use on the product label on the bottle.

## Can Antiseptix Multi Surface Disinfectant be used on electronics?

Yes. However, spray onto a cloth first - not directly on the electronic device - before wiping.

## Is Antiseptix Multi Surface Disinfectant recyclable?

Antiseptix Multi Surface Disinfectant, along with all Antiseptix products are recyclable. We urge our customers to tear off the label of the Antiseptix Multi Surface Disinfectant  bottle using the perforated peal. All components can we be recycled. A thank you in advanced for helping us recycle and save the environment.



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