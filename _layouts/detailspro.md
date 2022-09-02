---
layout: rootpro
---
<div class="container p-sm-5 pt-5">
    <div class="row pt-sm-5 mt-5">
        <div class="col-12">
            {% include breadcrumbs.html %}
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start py-5">
            <img src="{{page.image}}" width="100%" />
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start">
            <h1>{{page.title}}</h1>
            <h2>{{page.subtitle}}</h2>
            <p>{{page.description}}<p>

            {% include amazonbutton.md %}
        
        </div>
        <div class="col-12">
            {{content}}
        </div>
    </div>
</div>
