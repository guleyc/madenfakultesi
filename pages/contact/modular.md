---
title: İletişim
menu: Contact
cache_enable: false
shown_in_footer: true
content:
    items: '@self.modular'
    order:
        by: default
        dir: asc
        custom:
            - _contact
            - _map
form:
    action: /contact
    name: contact-form
    fields:
        -   name: name
            label: Name
            placeholder: Adınız
            type: text
            validate:
                required: true
            classes: form-control
        -   name: email
            label: Email
            placeholder: 'Email adresiniz'
            type: email
            validate:
                required: true
            classes: form-control
        -   name: message
            label: Message
            placeholder: 'Yazmak istediğiniz mesajınız'
            type: textarea
            rows: 6
            validate:
                required: true
            classes: form-control
        -   name: g-recaptcha-response
            label: Captcha
            type: captcha
            recaptcha_site_key: 6LdwPkIUAAAAAIbOI4BK6ADlTeJ6AEBvq7VOmTV8
            recaptcha_not_validated: 'Captcha not valid!'
            validate:
            required: true
    buttons:
        -   type: submit
            value: 'Gönder'
            classes: 'btn btn-primary'
    process:
        -   captcha:
                recaptcha_secret: 6LdwPkIUAAAAAEtef5rjyziNN8Ob13YLXpfTfV-g
        -   email:
                from: '{{ config.plugins.email.from }}'
                to: ['{{ config.plugins.email.from }}']
                subject: '[İletişim] {{ form.value.name|e }}'
                body: '{% include ''forms/data.html.twig'' %}'
        -   save:
                fileprefix: contact-
                dateformat: Ymd-His-u
                extension: txt
                body: '{% include ''forms/data.txt.twig'' %}'
        -   display: thank-you
---