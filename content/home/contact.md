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
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Follow Me
      link: 'https://twitter.com/pelayoarbues'
    - icon: linkedin
      icon_pack: fab
      name: Add Me
      link: 'https://linkedin.com/in/pelayoarbues'


design:
  columns: '2'
---
