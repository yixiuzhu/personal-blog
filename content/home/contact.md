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
  email: zhuyixiu06@gmail.com
  phone: (857)-800-2044
  address:
    street: 771 Beacon Street, Apt 802
    city: Boston
    region: MA
    postcode: '02215'
    country: United States
    country_code: US
  coordinates:
    latitude: '42.2050'
    longitude: '-71.0602'
  directions: Enter bowers apartment and ask the front desk
  # office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/zhu_yixiu'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://us05web.zoom.us/j/83721722519?pwd=dmVRY0h5RTNJK0ZiODNvek5PUDBYQT09'

design:
  columns: '2'
---
