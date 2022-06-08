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

  # Contact (edit or remove options as required)

  email: etienne.peillard@imt-atlantique.fr
  phone: +33 2 29 00 10 19
  address:
    street: Technopôle Brest-Iroise CS 83818
    city: Brest Cedex 3
    postcode: '29238'
    country: France
    country_code: FR
  coordinates:
    latitude: '48.358833'
    longitude: '-4.570972'
  directions: From main entrance, go to the main hall and then follow "Building D3 - Département informatique" signs, to office D3-107 on Floor 1.  
  office_hours:
    - 'Monday to Friday 9:00 to 18:30'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM me on Twitter
      link: 'https://twitter.com/EPeillard'
    - icon: linkedin
      icon_pack: fab
      name: DM me on LinkedIn
      link: 'https://www.linkedin.com/in/etienne-peillard-81012182/'
    # - icon: skype
    #   icon_pack: fab
    #   name: Skype Me
    #   link: 'skype:echo123?call'
    # - icon: keybase
    #   icon_pack: fab
    #   name: Chat on Keybase
    #   link: 'https://keybase.io/'
    # - icon: comments
    #   icon_pack: fas
    #   name: Discuss on Forum
    #   link: 'https://discourse.gohugo.io'

design:
  columns: '2'
---
