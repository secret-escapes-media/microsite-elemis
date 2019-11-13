---
layout: content
id: the-house-of-elemis
permalink: /the-house-of-elemis/
title: The House of ELEMIS
nav: true
nav-order: 4
content-page: true
intro: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
extra-intro-content: >
  <p>Voucher content - Get a free product quoting us when booking</p>
  <p>BOOKINGCODETOQUOTE</p>
  <div class="space--sm"></div>
  <a id="track-{{page.id}}-intro-btn" href="https://www.elemis.com/house-of-elemis-london" class="btn btn--outline btn--outline-blue">MAKE A BOOKING ENQUIRY</a>


treatments:

  - id: pro-collagen-age-defy
    title: PRO-COLLAGEN AGE DEFY
    description: Tackle fine lines and wrinkles with the clinically proven* age-defying benefits of marine charged Padina Pavonica and Red Coral. Targeted massage encourages optimum cellular function for nourished, younger looking skin. *Independent Clinical Trials
    time: 1 hour
    price: 115
    link: https://www.elemis.com/house-of-elemis-treatment-menu-face

  - id: biotec-line-eraser
    title: BIOTEC LINE ERASER
    description: Target wrinkles and energise the skin towards optimum performance with microcurrent pulses and red and blue light therapy. A powerfully rejuvenating clinically proven* facial treatment that effectively irons out wrinkles and fills out lines.*Independent Clinical Trial.
    time: 1 hour
    price: 125
    link: https://www.elemis.com/house-of-elemis-treatment-menu-face

  - id: freestyle-deep-tissue-massage
    title: FREESTYLE DEEP TISSUE MASSAGE
    description: Your therapist will select an aromatic oil according to your concerns, be they muscle pain, stress relief, relaxation or balance. The flowing massage works deeper into the tension, encouraging optimum circulation.
    time: 1 hour
    price: 95
    link: https://www.elemis.com/house-of-elemis-treatment-menu-body#massage

  - id: poultice-powered-muscle-release
    title: POULTICE-POWERED MUSCLE RELEASE
    description: Sore, aching muscles are worked away with this invigorating and deeply releasing treatment. Each area of tension is specifically targeted with the unique Amber and Quartz poultice to dissolve knots and ease tensions. Completed with a restorative facial massage, tension is dissolved.
    time: 1 hour
    price: 115
    link: https://www.elemis.com/house-of-elemis-treatment-menu-body#massage


features:

  - id: the-penthouse
    title: THE PENTHOUSE
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.

  - id: therapists
    title: ELEMIS Elite therapists
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.

---

<div class="vpad--xxl">
  <div class="container">
    {% for item in page.features %}
      <div class="bob{% cycle '', ' bob--swap' %}">
        <div class="bob__img">
          <div class="bg-img bg-img--3-2" style="background-image: url('{{site.img}}/content/{{page.id}}/{{item.id}}.jpg');"></div>
        </div>
        <div class="bob__text">
          <h2 class="title title--md title--color">{{item.title}}</h2>
          <p class="text--xl">{{item.description}}</p>
        </div>
      </div>
    {% endfor %}
  </div>
</div>

<div class="vpad--xxl bg--light">
  <div class="container container--xxl">
    <h2 class="title title--lg title--color text--center width width--lg">Bestselling Facials & Body&nbsp;Treatments</h2>
    <div class="space--xl"></div>
    <div class="row row--6-6 row--gutters-lg">
      {% for treatment in page.treatments %}
        <div class="col">
          <div class="bg-img bg-img--4-3" style="background-image: url('{{site.img}}/img.jpg');">
            <a id="track-{{page.id}}-{{treatment.id}}-img" class="bg-img__link" href="{{treatment.link}}"></a>
          </div>
          <div class="boxpad--lg bg--white">
            <h3 class="title title--xs title--color">{{treatment.title}}</h3>
            <p>{{treatment.description}}</p>
            <p class="text--xxl text--normal title--color">{{treatment.time}} £{{treatment.price}}</p>
            <div class="space--sm"></div>
            <a id="track-{{page.id}}-{{treatment.id}}-btn" href="{{treatment.link}}" class="btn btn--sm btn--outline btn--outline-blue">Book Now</a>
          </div>
        </div>
      {% endfor %}
    </div>
    <div class="space--xl text--center">
      <a id="track-{{page.id}}-all-treatments-btn" href="https://www.elemis.com/house-of-elemis-treatment-menu-face" class="btn btn--lg btn--blue">See More Treatments</a>
    </div>
  </div>
</div>