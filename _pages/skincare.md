---
layout: content
id: skincare
permalink: /skincare/
title: Skincare
nav: true
nav-order: 3
content-page: true
banner-title: Refresh Your Skincare routine With an Exclusive 20% Off Luxurious Elemis Products*
intro: Find your next skincare routine here. Defined by nature and led by science, ELEMIS sources only the finest ingredients from above and below the earth’s surface. Pioneering and transformative formulas utilise these organic ingredients for award-winning results. It’s this innovation that creates a skincare range which truly set ELEMIS apart – making them The No.1 British Luxury Skincare Brand.
intro-content: >
  <div class="vpad--xl width width--lg text--center">
    <p class="text--xxl">{{page.intro}}</p>
    <p class="text--xxl">Don’t take our word for it; try the products for yourself with an exclusive 20% discount for Secret Escapes members! Simply enter the below code at checkout:</p>
    <div class="vpad--xs width width--md">
      <div class="promo-code">SEVIP20</div>
    </div>
    <a id="track-{{page.id}}-intro-btn" href="https://www.elemis.com/skincare" class="btn btn--blue">Shop Skincare Now</a>
  </div>


features:

  - id: ultra-smart-pro-collagen
    title: ULTRA SMART <span class="dont-break-hyphen">PRO-COLLAGEN</span>
    sub-title: Intelligent Skincare
    description: Discover a range of uniquely engineered treatments that give you the resilient appearance of younger skin. This is the age of intelligent skincare.
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle/ultra-smart-pro-collagen

  - id: pro-collagen
    title: PRO-COLLAGEN
    sub-title: Anti-Ageing Solutions
    description: Rich marine and plant actives combine in the world-renowned Pro-Collagen formulations. Reduce the appearance of fine lines and wrinkles and delicately smooth your skin.
    link: https://www.elemis.com/skincare/pro-collagen-anti-wrinkle

  - id: dynamic-resurfacing
    title: DYNAMIC RESURFACING
    sub-title: Daily Resurfacing & Renewal
    description: Boost your complexion and make your skin positively vibrant with daily resurfacing and renewal formulas. Patented Tri-Enzyme technology restores even skin tone and gives you fresher, brighter skin.
    link: https://www.elemis.com/skincare/resurfacing-tri-enzyme

  - id: peptide-24-7
    title: PEPTIDE 24/7
    sub-title: Skin Wellness
    description: The skin-renewing Peptide 24/7 range targets tired-looking skin around the clock. Achieve a well-rested glow everyday all-day with this luxurious formula.
    link: https://www.elemis.com/skincare/peptide4

  - id: superfood
    title: SUPERFOOD
    sub-title: Skin Health & Nutrition
    description: Nutrient-dense superfoods combine with a natural, sugar-derived prebiotic to create a skincare system that replenishes skin. With vital hydrating nourishment, get a healthy, outdoor-fresh glow.
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