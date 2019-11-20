---
layout: competition
id: competition
permalink: /competition/
nav: true
nav-order: 5

title: Compet&shy;ition
long-title: Win an opulent spa escape plus £1000 ELEMIS shopping spree
intro: In the idyllic and historic spa town of Harrogate sits Rudding Park, a gorgeous manor getaway where luxury and relaxation await. From long spa dips to private cinema screenings, luxury skincare spends and exquisite dining, this competition is set to replenish even the most wearied traveller.
enter-cta: Enter Now

features:

  - id: rudding-park
    title: Stay at the Exquisite Rudding Park Hotel
    description: Enjoy a two-night B&B stay in the gorgeous Follifoot Wing Room at Rudding Park, where contemporary design meets classic manor charms. Enjoy dinner one night at your choice of restaurants – the award-winning Horto, or laidback Clocktower, and spend the other night kicking back in the hotel’s cinema for a private screening with champagne and popcorn.

  - id: experiences
    title: Get Fully Pampered in the Hotel Spa
    description: For the duration of your stay, you’ll have unlimited access to Rudding Park’s exclusive spa. Reset with hydrotherapy and thermal experiences in the rooftop spa and garden, before indulging in a bespoke treatment for you and your plus one.

  - id: voucher
    title: Go on a £1000 ELEMIS Shopping Spree
    description: Your wellness escape doesn’t end here; refresh your beauty regime with £1000 to spend at ELEMIS. Fill your shopping basket with products by Britain’s no.1 luxury skincare company and revitalise your skincare rituals.


competition-form:
  id: comp
  post-url: "#getFormUrl"
  expiry-date: 2050-01-01
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
      label: Would you like to receive emails from our Partner brand?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
    - id: storytime
      type: text-long
      label: Tell us about your favourite travel experience
      required: true
    - id: eggs
      type: select
      label: What is your favourite continent?
      required: true
      options:
        - label: Africa
          value: africa
        - label: Antarctica
          value: antarctica
        - label: Asia
          value: asia
        - label: Europe
          value: europe
        - label: North America
          value: north-america
        - label: Oceania
          value: oceania
        - label: South America
          value: south-america
    - id: contact
      type: checkbox
      label: Do you have a preference on how we should contact you?
      required: true
      options:
        - id: contact-email
          label: Email
          value: email
        - id: contact-post
          label: Post
          value: post
        - id: contact-phone
          label: Phone
          value: phone
    - id: week
      type: select
      label: What is your favourite day of the week?
      options:
        - label: Monday
          value: mon
        - label: Tuesday
          value: tue
        - label: Wednesday
          value: wed
        - label: Thursday
          value: thur
        - label: Friday
          value: fri
        - label: Saturday
          value: sat
        - label: Sunday
          value: sun
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---