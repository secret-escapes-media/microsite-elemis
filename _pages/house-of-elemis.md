---
layout: content
id: the-house-of-elemis
permalink: /the-house-of-elemis/
title: The House of ELEMIS
nav: true
nav-order: 4
content-page: true
banner:
  title: >
    The House <br class="desktop-break">of ELEMIS
intro: Take your beauty routine one step further by dropping in at the House of ELEMIS. Located in the heart of exclusive Mayfair, indulge in sumptuous treatments at the hands of ELEMIS Elite therapists, who will personalise your experience to give you only the best, most transformative results. Pick your perfect treatment below…
intro-content: >
  <div class="vpad--xl">
    <div class="width width--lg text--center">
      <p class="text--xxl">{{page.intro}}</p>
    </div>
    <div class="space--lg"></div>
    <div class="width width--xl boxpad--xl bg--promo text--blue">
      <div class="row row--start">
        <div class="col col--7">
          <div class="vpad--sm">
            <h3 class="title title--color title--xs">Exclusive House of ELEMIS offer for Secret Escapes members</h3>
            <p class="text--normal">Book any 60-minute treatment at The House of ELEMIS and get an exclusive 20% off!</p>
            <p class="text--normal">Make sure you quote “<strong>Secret Escapes</strong>” when you book to claim your discount.</p>
            <div class="vpad--xxs"></div>
            <a id="track-{{page.id}}-promo-btn" href="https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-booking-enquiry" class="btn btn--sm btn--blue">MAKE A BOOKING ENQUIRY</a>
          </div>
        </div>
      </div>
    </div>
  </div>
terms-and-conditions:
  - >
    {{site.house-of-elemis-tandcs}}
  - "**Independent Clinical Trials"


treatments:

  - id: pro-collagen-age-defy
    title: PRO-COLLAGEN AGE DEFY
    description: Tackle fine lines and wrinkles with the clinically proven age-defying benefits of marine charged Padina Pavonica and Red Algae. Targeted massage encourages optimum cellular function for nourished, younger looking skin**.
    time: 1 hour
    price: 115
    link: https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-treatment-menu-face

  - id: biotec-line-eraser
    title: BIOTEC LINE ERASER
    description: Target wrinkles and energise the skin towards optimum performance with microcurrent pulses and red and blue light therapy. A powerfully rejuvenating clinically proven facial treatment that effectively irons out wrinkles and fills out lines**.
    time: 1 hour
    price: 125
    link: https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-treatment-menu-face

  - id: freestyle-deep-tissue-massage
    title: FREESTYLE DEEP TISSUE MASSAGE
    description: Your therapist will select an aromatic oil according to your concerns, be they muscle pain, stress relief, relaxation or balance. The flowing massage works deeper into the tension, encouraging optimum circulation.
    time: 1 hour
    price: 95
    link: https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-treatment-menu-body%23massage

  - id: poultice-powered-muscle-release
    title: POULTICE-POWERED MUSCLE RELEASE
    description: Sore, aching muscles are worked away with this invigorating and deeply releasing treatment. Each area of tension is specifically targeted with the unique Amber and Quartz poultice to dissolve knots and ease tensions. Completed with a restorative facial massage, tension is dissolved.
    time: 1 hour
    price: 115
    link: https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-treatment-menu-body%23massage
---

<div class="container vpad--xxl">
  <div class="width width--xxl">
    <h2 class="title title--lg title--color text--center width width--lg">Bestselling Facials & Body Treatments</h2>
    <div class="space--xl"></div>
    <div class="row row--6-6 row--gutters-lg">
      {% for treatment in page.treatments %}
        <div class="col">
          <div class="bg-img bg-img--4-3" style="background-image: url('{{site.img}}/content/{{page.id}}/{{treatment.id}}.jpg');">
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
      <a id="track-{{page.id}}-all-treatments-btn" href="https://click.linksynergy.com/deeplink?id=rg1rVdkt0EQ&mid=42744&murl=https%3A%2F%2Fwww.elemis.com%2Fhouse-of-elemis-treatment-menu-face" class="btn btn--lg btn--blue">See More Treatments</a>
    </div>
  </div>
</div>