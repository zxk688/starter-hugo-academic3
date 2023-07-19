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
  email: natezhangxk@gmail.com
  address:
    street: 181 Chatham Road South
    city: Hung Hom
    region: Kowloon
    postcode: '518172'
    country: Hong Kong
    country_code: CHN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Block Z


design:
  columns: '2'
---
