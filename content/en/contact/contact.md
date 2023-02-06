---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
<div style="width: 50%;">
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Contact
subtitle:

content:
  # Contact (edit or remove options as required)

  email: xuelian@acssz.org
#  appointment_url: 'https://calendly.com'
# contact_links:
#    - icon: comments
#      icon_pack: fas
#      name: Discuss on Forum
#      link: 'https://discourse.gohugo.io'

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

design:
  columns: '1'
</div><div style="width: 50%;">
widget: blank

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title:
subtitle:

design:
  columns: '1'
  background:
    image: QRcode.jpg
    image_darken: 0
    image_parallax: false
    image_position: center
    image_size: cover
    text_color_light: true
  spacing:
    padding: ['20px', '0', '20px', '0']
</div>
---
