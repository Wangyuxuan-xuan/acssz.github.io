---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/

### widget: contact

# This file represents a page section.
### headless: true

# Order that this section appears on the page.
### weight: 10
### title: Contact
### subtitle:

### content:
  # Contact (edit or remove options as required)

### email: inthink18z@gmail.com
#  appointment_url: 'https://calendly.com'
# contact_links:
#    - icon: comments
#      icon_pack: fas
#      name: Discuss on Forum
#      link: 'https://discourse.gohugo.io'

  # Automatically link email and phone or display as text?
###  autolink: true

### design:
    ### columns: '1'
# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: ''
      email: inthink18z@gmail.com
      autolink: true
      form:
        provider: formspree
        formspree:
          id: xknajwaq
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
---
