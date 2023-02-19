---
layout: rootpro
---
<div class="container p-sm-5 pt-5 productdetailspage">
    <div class="row pt-sm-5 mt-5">
        <div class="col-8 offset-2">
            <a class="btn btn-primary col-12 d-sm-none" href="{{site.baseurl}}/pro/" role="button">&laquo; Back to Products</a>
            <!-- <a class="btn btn-primary col-12 d-sm-none" href="{{site.baseurl}}/pro/products/" role="button">&laquo; Back to Products</a> -->
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start py-5 productdetailspageimage">
            <img src="{{page.image}}" width="100%" />
        </div>
        <div class="col-12 col-sm-6 text-center text-sm-start">
            <div class="d-none d-sm-block pt-5">
            {% include breadcrumbs.html %}
            </div>
            <h1 class="py-3 px-3 px-sm-0">{{page.title}}</h1>
            <h2 class="py-3 px-3 px-sm-0">{{page.subtitle}}</h2>

                        {% include amazonbutton.md %}

            {% include buynow.md %}

            <!--<p class="mt-3">
                <a class="btn btn-outline-secondary btn-lg" href="#typeform" data-tf-popup="yn2qHgdC" data-tf-iframe-props="title=AntiSeptix Sales" data-tf-medium="snippet" >Contact Us</a>
            </p>-->

            <div class="accordion mt-5 mb-4" id="accordionDescription">
  <div class="accordion-item border border-0 border-top border-bottom bg-transparent">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button collapsed bg-transparent text-dark px-3 px-sm-0" type="button" data-bs-toggle="collapse" data-bs-target="#collapseDescription" aria-expanded="false" aria-controls="collapseDescription">
        <strong>Show Full Description</strong>
      </button>
    </h2>
    <div id="collapseDescription" class="accordion-collapse collapse hide" aria-labelledby="headingOne" data-bs-parent="#accordionDescription">
      <div class="accordion-body px-3 px-sm-0">
        <p>{{page.description}}<p>
      </div>
    </div>
  </div>
 <div class="accordion-item border border-0 border-top border-bottom bg-transparent">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed bg-transparent text-dark px-3 px-sm-0" type="button" data-bs-toggle="collapse" data-bs-target="#collapseInstructions" aria-expanded="false" aria-controls="collapseInstructions">
        <strong>How to Use</strong>
      </button>
    </h2>
    <div id="collapseInstructions" class="accordion-collapse collapse hide" aria-labelledby="headingTwo" data-bs-parent="#accordionInstructions">
      <div class="accordion-body px-3 px-sm-0">
        <ol>
        {% for i in page.instructions %}
            <li> {{ i }}</li>
        {% endfor %}
        </ol>
      </div>
    </div>
  </div>
  <div class="accordion-item border border-0 border-top border-bottom bg-transparent">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed bg-transparent text-dark px-3 px-sm-0" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSafety" aria-expanded="false" aria-controls="collapseSafety">
        <strong>Safety Instructions</strong>
      </button>
    </h2>
    <div id="collapseSafety" class="accordion-collapse collapse hide" aria-labelledby="headingTwo" data-bs-parent="#accordionSafety">
      <div class="accordion-body px-3 px-sm-0">
        <ul>
        {% for i in page.safety %}
            <li> {{ i }}</li>
        {% endfor %}
        </ul>
      </div>
    </div>
  </div>
<div class="accordion-item border border-0 border-top border-bottom bg-transparent">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed bg-transparent text-dark px-3 px-sm-0" type="button" data-bs-toggle="collapse" data-bs-target="#collapseIngredients" aria-expanded="false" aria-controls="collapseIngredients">
        <strong>Ingredients</strong>
      </button>
    </h2>
    <div id="collapseIngredients" class="accordion-collapse collapse hide" aria-labelledby="headingTwo" data-bs-parent="#accordionIngredients">
      <div class="accordion-body px-3 px-sm-0">
        <ul>
        {% for i in page.ingredients %}
            <li> {{ i }}</li>
        {% endfor %}
        </ul>
      </div>
    </div>
  </div>
  <div class="accordion-item border border-0 border-top border-bottom bg-transparent">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed bg-transparent text-dark px-3 px-sm-0" type="button" data-bs-toggle="collapse" data-bs-target="#collapseStorage" aria-expanded="false" aria-controls="collapseStorage">
        <strong>Storage</strong>
      </button>
    </h2>
    <div id="collapseStorage" class="accordion-collapse collapse hide" aria-labelledby="headingTwo" data-bs-parent="#accordionStorage">
      <div class="accordion-body px-3 px-sm-0">
        <ul>
        {% for i in page.storage %}
            <li> {{ i }}</li>
        {% endfor %}
        </ul>
      </div>
    </div>
  </div>

</div>
            


            
        
        </div>
        <div class="col-12">
            {{content}}
        </div>
    </div>
</div>


<div class="container-fluid g-0 ps-3 ps-md-5 py-5">
    <div class="container-fluid py-5 py-sm-3 py-md-5 bg-image bg-image1 text-dark text-center rounded-pill-start">
        <h2>Features</h2>
        <div class="row p-5">
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/2756/2756759.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Kills Viruses (coronavirus, poliovirus, norovirus, flu, adenovirus)</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/2913/2913465.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Covid-19</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/5376/5376524.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Kills Bacteria (e. coli, salmonella)</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-virus2" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M8 0a1 1 0 0 0-1 1v1.143c0 .557-.407 1.025-.921 1.24-.514.214-1.12.162-1.513-.231l-.809-.809a1 1 0 1 0-1.414 1.414l.809.809c.393.394.445.999.23 1.513C3.168 6.593 2.7 7 2.142 7H1a1 1 0 0 0 0 2h1.143c.557 0 1.025.407 1.24.921.214.514.162 1.12-.231 1.513l-.809.809a1 1 0 0 0 1.414 1.414l.809-.809c.394-.394.999-.445 1.513-.23.514.214.921.682.921 1.24V15a1 1 0 1 0 2 0v-1.143c0-.557.407-1.025.921-1.24.514-.214 1.12-.162 1.513.231l.809.809a1 1 0 0 0 1.414-1.414l-.809-.809c-.394-.394-.445-.999-.23-1.513.214-.514.682-.921 1.24-.921H15a1 1 0 1 0 0-2h-1.143c-.557 0-1.025-.407-1.24-.921-.214-.514-.163-1.12.231-1.513l.809-.809a1 1 0 1 0-1.415-1.414l-.808.809c-.394.393-.999.445-1.513.23C9.407 3.168 9 2.7 9 2.142V1a1 1 0 0 0-1-1Zm2 5a1 1 0 1 1-2 0 1 1 0 0 1 2 0ZM7 7a1 1 0 1 1-2 0 1 1 0 0 1 2 0Zm1 5a1 1 0 1 0 0-2 1 1 0 0 0 0 2Zm4-4a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"/>
                    </svg>
                </div>
                <div class="col-12 py-3">
                    <p>Kills Fungus</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/4939/4939134.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Non-Toxic – safe for your skin</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/4441/4441209.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Child safe</p>
                </div>
            </div>
            <!--<div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/4231/4231117.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Chemical free</p>
                </div>
            </div>-->
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/5971/5971948.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Food safe</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/5769/5769356.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Vegan</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/9436/9436972.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>Pet safe</p>
                </div>
            </div>
            <div class="col-12 col-sm-3">
                <div class="col-12 py-3">
                    <img src="https://cdn-icons-png.flaticon.com/512/6889/6889429.png" class="product-features-icon" />
                </div>
                <div class="col-12 py-3">
                    <p>100% natural</p>
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
    <div class="container-fluid py-5 py-sm-3 py-md-5 bg-image bg-image3 text-dark rounded-pill-end">
        <div class="row p-5">

            <div class="col-12 col-md-4">
                <div class="col-12 col-md-12">
                    <h2>How to Use</h2>
                    <ol>
                        {% for i in page.instructions %}
                            <li> {{ i }}</li>
                        {% endfor %}
                    </ol>
                    
                </div>
                <div class="col-12 col-md-12">
                    <h2>Ingredients</h2>
                    <ul>
                        {% for i in page.ingredients %}
                            <li> {{ i }}</li>
                        {% endfor %}
                    </ul>
                </div>
            </div>

            <div class="col-12 col-md-8 row">
                <div class="col-12 col-md-6">
                    <h2>Safety Instructions</h2>
                    <ul>
                        {% for i in page.safety %}
                            <li> {{ i }}</li>
                        {% endfor %}
                    </ul>
                </div>
                <div class="col-12 col-md-6">
                    <h2>Storage</h2>
                    <ul>
                        {% for i in page.storage %}
                            <li> {{ i }}</li>
                        {% endfor %}
                    </ul>
                </div>
            </div>

        </div>
    </div>
</div>

