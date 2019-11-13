---
layout: content
id: skincare
permalink: /skincare/
title: Skincare
nav: true
nav-order: 3
content-page: true
banner-title: Experience skincare crafted by the chemistry of nature
intro: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
extra-intro-content: >
  <p>Voucher content - save 20% off all Elemis products</p>
  <p>EXACTVOUCHERCODE</p>
  <div class="space--sm"></div>
  <a id="track-{{page.id}}-intro-btn" href="{{feature.link}}" class="btn btn--outline btn--outline-blue">Shop Skincare Now</a>


features:

  - id: ultra-smart-pro-collagen
    title: ULTRA SMART PRO-COLLAGEN
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle/ultra-smart-pro-collagen

  - id: pro-collagen
    title: PRO-COLLAGEN
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle

  - id: dynamic-resurfacing
    title: DYNAMIC RESURFACING
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
    link: https://www.elemis.com/skincare/resurfacing-tri-enzyme

  - id: peptide-24-7
    title: PEPTIDE 24/7
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
    link: https://www.elemis.com/skincare/peptide4

  - id: superfood
    title: SUPERFOOD
    description: Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consectetur aspernatur beatae tempora, voluptates ut recusandae ea exercitationem culpa mollitia quia similique. Perferendis cumque obcaecati ad pariatur. Quos iure sapiente amet beatae, officiis possimus minima expedita, ea ad. Doloribus et perspiciatis doloremque.
    link: https://www.elemis.com/skincare/superfood

---

{% for feature in page.features %}
  <div class="harvey{% cycle '', ' harvey--swap' %}">
    <div class="harvey__img" style="background-image: url('{{site.img}}/content/{{page.id}}/{{feature.id}}.jpg');">
      <a id="track-{{page.id}}-{{feautre.id}}-img" class="harvey__link" href="{{feature.link}}"></a>
    </div>
    <div class="harvey__text">
      <h3 class="title title--md title--color">{{feature.title}}</h3>
      <p class="text--xxl">{{feature.description}}</p>
      <div class="space--sm"></div>
      <a id="track-{{page.id}}-{{feautre.id}}-btn" href="{{feature.link}}" class="btn btn--blue">Shop The Range</a>
    </div>
  </div>
{% endfor %}