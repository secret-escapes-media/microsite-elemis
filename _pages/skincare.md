---
layout: content
id: skincare
permalink: /skincare/
title: Skincare
nav: true
nav-order: 3
content-page: true
banner-title: Refresh Your Skincare routine With an Exclusive 20% Off Award-Winning ELEMIS Skincare*
intro: Find your next skincare routine here. Defined by nature and led by science, ELEMIS sources only the finest ingredients from above and below the earth’s surface. Pioneering and transformative formulas utilise these organic ingredients for award-winning results. It’s this innovation that creates a skincare range which truly set ELEMIS apart – making them The No.1 British Luxury Skincare Brand.
intro-content: >
  <div class="vpad--xl width width--lg text--center">
    <p class="text--xxl">{{page.intro}}</p>
    <p class="text--xxl">Don’t take our word for it; try the products for yourself with an exclusive 20% off your first order, only for Secret Escapes members!* Simply enter the below code at checkout:</p>
    <div class="vpad--xs width width--md">
      <div class="promo-code">SEVIP20</div>
    </div>
    <a id="track-{{page.id}}-intro-btn" href="https://www.elemis.com/skincare" class="btn btn--blue">Shop Skincare Now</a>
  </div>
terms-and-conditions: "**Independent Clinical Trials 2018"


features:

  - id: ultra-smart-pro-collagen
    title: ULTRA SMART <span class="dont-break-hyphen">PRO-COLLAGEN</span>
    sub-title: Intelligent Skincare
    description: "High Performance Algae meets Targeted Delivery Systems. Clinically proven to deliver transformative results in just 28 days.**"
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle/ultra-smart-pro-collagen

  - id: pro-collagen
    title: PRO-COLLAGEN
    sub-title: Anti-Ageing Solutions
    description: Combining powerful marine actives with antioxidant-rich plant extracts, stem cells and innovative delivery systems, Pro-Collagen is a clinically proven, award-winning line that targets multiple signs of ageing, from fine lines and wrinkles, to loss of firmness and elasticity.
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle

  - id: dynamic-resurfacing
    title: DYNAMIC RESURFACING
    sub-title: Daily Resurfacing & Renewal
    description: ELEMIS Dynamic Resurfacing Collection is formulated with patented Tri-Enzyme Technology to resurface the skin and encourage accelerated cell turnover for improved skin clarity, texture and tone.
    link: https://www.elemis.com/skincare/resurfacing-tri-enzyme

  - id: peptide-24-7
    title: PEPTIDE 24/7
    sub-title: Skin Wellness
    description: Multi-tasking treatments that support the skin’s natural processes of defence by day and repair by night.  Leaves the skin looking refreshed, renewed and radiant for a well-rested complexion 24/7.
    link: https://www.elemis.com/skincare/peptide4

  - id: superfood
    title: SUPERFOOD
    sub-title: Skin Health & Nutrition
    description: Prebiotic skincare that balances the skin’s microbiome and feeds the skin with vitamin-packed Superfoods for a healthy-looking glow.
    link: https://www.elemis.com/skincare/superfood

---

{% for feature in page.features %}
  <div class="harvey{% cycle '', ' harvey--swap' %}">
    <div class="harvey__img" style="background-image: url('{{site.img}}/content/{{page.id}}/{{feature.id}}.jpg');">
      <a id="track-{{page.id}}-{{feautre.id}}-img" class="harvey__link" href="{{feature.link}}"></a>
    </div>
    <div class="harvey__text">
      <h3 class="title title--lg title--color">{{feature.title}}</h3>
      <h4 class="title title--xxs">{{feature.sub-title}}</h4>
      <p class="text--xxl">{{feature.description}}</p>
      <div class="space--sm"></div>
      <a id="track-{{page.id}}-{{feautre.id}}-btn" href="{{feature.link}}" class="btn btn--blue">Shop The Range</a>
    </div>
  </div>
{% endfor %}