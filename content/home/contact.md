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
  email: lyzhou@link.cuhk.edu.hk
  address:
    street: 12 Horse Material Water
    city: Hong Kong
    region: Shatin
    postcode: '999077'
    country: China
    country_code: CN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'

design:
  columns: '2'
---
