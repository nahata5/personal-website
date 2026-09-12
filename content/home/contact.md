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
  # form:
  #   provider: netlify
  #   formspree:
  #     id:
  #   netlify:
  #     # Enable CAPTCHA challenge to reduce spam?
  #     captcha: false

  # Contact details (edit or remove options as required)
  # Email is exposed as a labelled link in `contact_links` below rather than as
  # plain text, so the address is not printed on the page.
  # phone: 888 888 88 88
  address:
    street: 1 Robert Wood Johnson Place
    city: New Brunswick
    region: NJ
    postcode: '08901'
    country: United States
    country_code: US
  # coordinates:
  #   latitude: '37.4275'
  #   longitude: '-122.1697'
  # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  # office_hours:
  #   - 'Monday 10:00 to 13:00'
  #   - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: envelope
      icon_pack: fas
      name: Email
      link: 'mailto:nahassta@rwjms.rutgers.edu'
    - icon: user-md
      icon_pack: fas
      name: Doximity
      link: 'https://www.doximity.com/pub/thomas-nahass-md'
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/tomnahass'
    # - icon: video
    #   icon_pack: fas
      # name: Zoom Me
      # link: 'https://zoom.com'

design:
  columns: '2'
---
