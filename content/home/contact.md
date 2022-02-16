---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: mrkusen@gmail.com
  phone: +66 0 91 792 8610
  address:
    city: Bangkok
    region: Thailand
    postcode: '10400'
    country: Thailand
    country_code: TH

design:
  columns: '2'
---
