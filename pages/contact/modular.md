---
title: İletişim
content:
    items: '@self.modular'
    order:
        by: default
        dir: asc
        custom:
            - _contact
            - _map
menu: Contact
cache_enable: false
twitterenable: true
twittercardoptions: summary
articleenabled: false
musiceventenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
eventenabled: false
personenabled: false
musicalbumenabled: false
productenabled: false
product:
    ratingValue: 2.5
restaurantenabled: false
restaurant:
    acceptsReservations: 'yes'
    priceRange: $
shown_in_footer: true
background_image: img-page-title.jpg
form:
    action: /contact
    name: contact-form
    fields:
        -
            name: name
            label: Name
            placeholder: Name
            type: text
            validate:
                required: true
            classes: form-control
        -
            name: email
            label: Email
            placeholder: 'Email Address'
            type: email
            validate:
                required: true
            classes: form-control
        -
            name: phone
            label: Phone
            placeholder: Phone
            type: text
            validate:
                required: true
            classes: form-control
        -
            name: message
            label: Message
            placeholder: 'Write Message'
            type: textarea
            rows: 6
            validate:
                required: true
            classes: form-control
    buttons:
        -
            type: submit
            value: 'Send Message'
            classes: 'btn btn-primary'
    process:
        -
            email:
                from: '{{ config.plugins.email.from }}'
                to: ['{{ config.plugins.email.from }}']
                subject: '[Contact] {{ form.value.name|e }}'
                body: '{% include ''forms/data.html.twig'' %}'
        -
            save:
                fileprefix: contact-
                dateformat: Ymd-His-u
                extension: txt
                body: '{% include ''forms/data.txt.twig'' %}'
        -
            display: thank-you
---

