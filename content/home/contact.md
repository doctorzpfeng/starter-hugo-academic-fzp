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
  email: zpfeng_1@stu.xidian.edu.cn
  address:
    street: 2nd Taibai Road
    city: Xi'an
    region: Shaanxi
    postcode: '710071'
    country: China
    country_code: China
  coordinates:
    latitude: '34.2309'
    longitude: '108.9168'
  directions: Enter Main Building (3rd section)  and take the stairs to Office 215 (South) on Floor 2
  office_hours:
    - 'Monday to Thursday 9:00 to 20:30'
    - 'Friday 09:00 to 17:00'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
