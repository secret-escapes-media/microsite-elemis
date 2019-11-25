---
layout: competition
id: competition
permalink: /competition/
nav: true
nav-order: 5

title: Compet&shy;ition
long-title: Win an opulent spa escape plus £1000 worth of ELEMIS products
intro: In the idyllic and historic spa town of Harrogate sits Rudding Park, a gorgeous manor getaway where luxury and relaxation await. From long spa dips to private cinema screenings, luxury skincare shopping spree and exquisite dining, this competition is set to replenish even the most wearied traveller.
enter-cta: Enter Now

features:

  - id: rudding-park
    title: Stay at the Exquisite Rudding Park Hotel
    description: Enjoy a two-night B&B stay in the gorgeous Follifoot Wing Room at Rudding Park, where contemporary design meets classic manor charms. Enjoy dinner one night at your choice of restaurants – the award-winning Horto, or laidback Clocktower, and spend the other night kicking back in the hotel’s cinema for a private screening with champagne and popcorn.

  - id: experiences
    title: Get Fully Pampered in the Hotel Spa
    description: For the duration of your stay, you’ll have unlimited access to Rudding Park’s exclusive spa. Reset with hydrotherapy and thermal experiences in the rooftop spa and garden, before indulging in a bespoke treatment for you and your plus one.

  - id: voucher
    title: Receive £1000 Worth of Elemis Products
    description: Your wellness escape doesn’t end here; refresh your beauty regime with £1000 of skincare products from ELEMIS. Enjoy a diverse selection of award-winning products by The No.1 British Luxury Skincare Brand and revitalise your skincare routine.


competition-form:
  id: comp
  post-url: "#getFormUrl"
  expiry-date: 2020-03-02
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: 'Yes'
          value: 'yes'
        - id: qualify-false
          label: 'No'
          value: 'no'
          invalid: true
    - id: opt-in
      type: radio
      label: I would like to sign up to be the first to discover exclusive offers, secret sales, and the latest product launches from ELEMIS. Sign up to join the ELEMIS family. For more information please view our <a class="link--underlined" href="https://www.elemis.com/privacy-policy">privacy&nbsp;policy</a>.*
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---