---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Please contact me via the email (evayfang@163.com).

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: formspree
    formspree:
      id: Yiwei Fang
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: true

  # Contact details (edit or remove options as required)
  email: evayfang@163.com
  phone: +86 137 2035 4991
  address:
    street: NO. 13 Hangkong Road
    city: Wuhan
    region: Hubei
    postcode: '430000'
    country: China
    country_code: CN
  coordinates:
    latitude: '30.58431'
    longitude: '114.25666'
  directions: ""
  office_hours:
    - 'Weekdays UTF+8 08:00 to 20:00'
    - 'Weekends UTF+8 09:00 to 17:00'
  # appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/evay_fang'
    #- icon: video
    #  icon_pack: fas
    #  name: Zoom Me
    #  link: 'https://zoom.com'

design:
  columns: '2'
---
