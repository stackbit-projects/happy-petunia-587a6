---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: |
      Veuillez remplir le court formulaire ci-dessous. 

      Nous vous recontacterons dans les meilleurs délais.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Nom
        is_required: true
      - input_type: text
        name: Company name
        label: Nom entreprise
        options: []
        is_required: false
        type: form_field
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: tel
        name: Phone numer
        label: Téléphone
        options:
          - Error on the site
          - Sponsorship
          - Other
        is_required: false
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          J'accepte que ce formulaire enregistre les informations que j'ai
          soumises afin que je puisse être contacté.
        is_required: true
    submit_label: Envoyer
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: landing
---
