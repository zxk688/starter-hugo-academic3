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
  email: zhangxiaokang@cuhk.edu.cn
  address:
    street: Longxiang Road
    city: Shenzhen
    region: Guangdong
    postcode: '518172'
    country: China
    country_code: CHN
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: Room 419, Chengdao Building


design:
  columns: '2'
---
