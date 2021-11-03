---
title: CONVERSEMOS
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: >
      Se sugiere contactarnos mediante
      [**Twitter**](https://twitter.com/Ed_FernandezG)**,** 
      [**Instagram**](https://www.instagram.com/blid.io/) ,
      [**Telegram**](https://t.me/blid_io) o
      [**Whatsapp**](https://wa.me/51945942289).


      Adicionalmente, puede contactarnos por correo, completando el siguiente
      formulario.
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Consulta gratis
          - Análisis de Datos
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
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
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
