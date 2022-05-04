---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: test@example.org
  address:
  Building of Management Academy, East Campus of University of Science and Technology of China. No. 96 Jinzhai Rd, Hefei,
  230026, Anhui Province, P.R.China    coordinates:
    latitude: '31.84722'
    longitude: '117.278453'
  directions: Enter Building of Management Academy and take the stairs to Office 501 on Floor 5
  #contact_links:
  #  - icon: comments
  #    icon_pack: fas
  #    name: Discuss on Forum
  #    link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
  # autolink: true

  # Email form provider
   form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

design:
  columns: '1'
---

