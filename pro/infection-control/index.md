---
layout: defaultnosplashpro
type: 
typepro: navright
sort: 2
title: Infection Control
css: d-none d-sm-block
thumbnail: https://images.unsplash.com/photo-1631941618536-2979d565b726?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2070&q=80
breadcrumbs: false
---
# {{page.title}}


Praesent nisi enim, vestibulum eget magna a, pulvinar cursus erat. Praesent nunc tortor, rutrum ac eros laoreet, sollicitudin malesuada elit. Nam sagittis blandit sem ac mattis.

## Nam eleifend enim lectus, nec condimentum neque posuere sed

Etiam consequat est eu pulvinar commodo. Praesent lacinia pulvinar finibus. Pellentesque ac tortor sapien. Proin et dui elementum, venenatis neque ut, lobortis justo

- Sed sit amet eros et sapien pellentesque suscipit
  - Faucibus massa ullamcorper
  - eget sollicitudin nulla sapien
- Nullam in odio nec risus ultricies scelerisque
- Quisque id maximus enim, in gravida nunc.

Maecenas scelerisque massa massa, ut fringilla sem tincidunt quis. Sed egestas purus ac purus aliquam ullamcorper. Cras vitae enim eget nisi vestibulum imperdiet. Cras id quam tincidunt, faucibus massa ullamcorper, posuere eros. Quisque vel sodales quam.

## Duis ac est ac massa tincidunt elementum

Sed venenatis ex ac erat varius, sed luctus elit finibus. Donec at lectus sed libero dignissim pellentesque sit amet vitae velit. Cras eget magna ac nunc aliquam commodo nec in velit.

Praesent porta, arcu eu tristique ornare, lectus leo volutpat dui, eget sollicitudin nulla sapien quis lectus. Fusce tristique, eros ut tincidunt ultrices, augue eros mattis augue, id fringilla ex est sed quam. Vestibulum in erat nec enim rhoncus lobortis.

<div class="container py-3 g-sm-0 subcardssections">
    <div class="row">
        {% assign sorted_applications = site.pages | where:"typepro", "infection-control" | sort: "sort" %}
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