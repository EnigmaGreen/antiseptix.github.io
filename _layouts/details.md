---
layout: root
---

<div class="container p-sm-5 pt-5 productdetailspage">
    <div class="row pt-sm-5 mt-5">
        <div class="col-8 offset-2">
            <a class="btn btn-primary col-12 d-sm-none" href="{{site.baseurl}}/products/" role="button">&laquo; Back to Products</a>
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start py-5 productdetailspageimage">
            <img src="{{page.image}}" width="100%" />
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start">
            <div class="d-none d-sm-block pt-5">
            {% include breadcrumbs.html %}
            </div>
            <h1 class="py-3">{{page.title}}</h1>
            <h2 class="py-3">{{page.subtitle}}</h2>
            <p>{{page.description}}<p>

            {% include amazonbutton.md %}
        
        </div>
        <div class="col-12">
            {{content}}
        </div>
    </div>
</div>

<div class="container-fluid g-0 ps-3 ps-md-5 py-5">
    <div class="container-fluid py-5 py-sm-3 py-md-5 bg-image bg-image1 text-light text-center rounded-pill-start">
        <h2>Features</h2>
        <div class="row p-5">
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-virus2" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M8 0a1 1 0 0 0-1 1v1.143c0 .557-.407 1.025-.921 1.24-.514.214-1.12.162-1.513-.231l-.809-.809a1 1 0 1 0-1.414 1.414l.809.809c.393.394.445.999.23 1.513C3.168 6.593 2.7 7 2.142 7H1a1 1 0 0 0 0 2h1.143c.557 0 1.025.407 1.24.921.214.514.162 1.12-.231 1.513l-.809.809a1 1 0 0 0 1.414 1.414l.809-.809c.394-.394.999-.445 1.513-.23.514.214.921.682.921 1.24V15a1 1 0 1 0 2 0v-1.143c0-.557.407-1.025.921-1.24.514-.214 1.12-.162 1.513.231l.809.809a1 1 0 0 0 1.414-1.414l-.809-.809c-.394-.394-.445-.999-.23-1.513.214-.514.682-.921 1.24-.921H15a1 1 0 1 0 0-2h-1.143c-.557 0-1.025-.407-1.24-.921-.214-.514-.163-1.12.231-1.513l.809-.809a1 1 0 1 0-1.415-1.414l-.808.809c-.394.393-.999.445-1.513.23C9.407 3.168 9 2.7 9 2.142V1a1 1 0 0 0-1-1Zm2 5a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM7 7a1 1 0 1 1-2 0 1 1 0 0 1 2 0Zm1 5a1 1 0 1 0 0-2 1 1 0 0 0 0 2Zm4-4a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"/>
                    </svg>
                </div>
                <div class="col-12 py-3">
                    <p>Kills 99.9% of bacteria and viruses*</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-droplet-half" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M7.21.8C7.69.295 8 0 8 0c.109.363.234.708.371 1.038.812 1.946 2.073 3.35 3.197 4.6C12.878 7.096 14 8.345 14 10a6 6 0 0 1-12 0C2 6.668 5.58 2.517 7.21.8zm.413 1.021A31.25 31.25 0 0 0 5.794 3.99c-.726.95-1.436 2.008-1.96 3.07C3.304 8.133 3 9.138 3 10c0 0 2.5 1.5 5 .5s5-.5 5-.5c0-1.201-.796-2.157-2.181-3.7l-.03-.032C9.75 5.11 8.5 3.72 7.623 1.82z"/>
                        <path fill-rule="evenodd" d="M4.553 7.776c.82-1.641 1.717-2.753 2.093-3.13l.708.708c-.29.29-1.128 1.311-1.907 2.87l-.894-.448z"/>
                    </svg>
                </div>
                <div class="col-12 py-3">
                    <p>Easy and convenient to use: No wiping required</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-house-heart-fill" viewBox="0 0 16 16">
                        <path d="M7.293 1.5a1 1 0 0 1 1.414 0L11 3.793V2.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v3.293l2.354 2.353a.5.5 0 0 1-.708.707L8 2.207 1.354 8.853a.5.5 0 1 1-.708-.707L7.293 1.5Z"/>
                        <path d="m14 9.293-6-6-6 6V13.5A1.5 1.5 0 0 0 3.5 15h9a1.5 1.5 0 0 0 1.5-1.5V9.293Zm-6-.811c1.664-1.673 5.825 1.254 0 5.018-5.825-3.764-1.664-6.691 0-5.018Z"/>
                    </svg>
                </div>
                <div class="col-12 py-3">
                    <p>Multi-surface: use anywhere in the home</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-sliders" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M11.5 2a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zM9.05 3a2.5 2.5 0 0 1 4.9 0H16v1h-2.05a2.5 2.5 0 0 1-4.9 0H0V3h9.05zM4.5 7a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zM2.05 8a2.5 2.5 0 0 1 4.9 0H16v1H6.95a2.5 2.5 0 0 1-4.9 0H0V8h2.05zm9.45 4a1.5 1.5 0 1 0 0 3 1.5 1.5 0 0 0 0-3zm-2.45 1a2.5 2.5 0 0 1 4.9 0H16v1h-2.05a2.5 2.5 0 0 1-4.9 0H0v-1h9.05z"/>
                    </svg>
                </div>
                <div class="col-12 py-3">
                    <p>Suitable for upholstery</p>
                </div>
            </div>
        </div>
    </div>
</div>


<div class="container-fluid g-0 py-sm-5 px-3 px-md-5">
    <div class="container-fluid bg-image bg-image2 rounded-pill-start rounded-pill-end p-sm-5">
        <div class="accordion px-3 px-sm-5 pb-5" id="accordionFAQs">

            <h2 class="text-center pt-3 pt-sm-0 pb-sm-3">FAQs</h2>

            {% for i in page.faqs %}

            <div class="accordion-item border border-0 border-top border-bottom bg-transparent">
            <h2 class="accordion-header" id="heading{{forloop.index}}">
            <button class="accordion-button collapsed bg-transparent text-dark" type="button" data-bs-toggle="collapse" data-bs-target="#collapse{{forloop.index}}" aria-expanded="false" aria-controls="collapse{{forloop.index}}">
                <strong>{{ i.q }}</strong>
            </button>
            </h2>
            <div id="collapse{{forloop.index}}" class="accordion-collapse collapse" aria-labelledby="heading{{forloop.index}}" data-bs-parent="#accordionExample">
            <div class="accordion-body p-sm-5">
                {{ i.a }}
            </div>
            </div>
        </div>
        
        {% endfor %}
        
        </div>
    </div>
</div>


<div class="container-fluid g-0 py-5 pe-3 pe-md-5">
    <div class="container-fluid py-5 py-sm-3 py-md-5 bg-image bg-image3 text-light rounded-pill-end">
        <div class="row p-5">
            <div class="col-12 col-md-4">
                <h2>How to Use</h2>
                <ol>
                    <li>Turn the spray nozzle to ‘ON’ position</li>
                    <li>Keep bottle upright, spray from 20- 25 cm away</li>
                    <li>Leave to work for up to 5 minutes</li>
                    <li>Wipe clean!</li>
                </ol>
            </div>
            <div class="col-12 col-md-4">
                <h2>Safety Instructions</h2>
                <ul>
                    <li>External use only.</li>
                    <li>When using this product, keep out of eyes, ears and mouth.</li>
                    <li>In case of contact with eyes, rinse thoroughly with water.</li>
                    <li>Keep out of reach of children.</li>
                    <li>If Swallowed seek medical attention if you feel unwell.</li>
                </ul>
            </div>
            <div class="col-12 col-md-4">
                <h2>Ingredients</h2>
                <ul>
                    <li>1% w/v Saline</li>
                </ul>
            </div>
        </div>
    </div>
</div>

