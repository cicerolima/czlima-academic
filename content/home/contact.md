---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle: Feel free to send me a message!

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
  email: czlima@gmail.com
  phone: +55 (11) 98812 5537
  address:
    street: 474 Itapeva St
    city: Sao Paulo
    region: SP
    postcode: '01332-000'
    country: Brazil
    country_code: BRA
  coordinates:
    latitude: '37.4275'
    longitude: '-122.1697'
  directions: 6th Floor
  #office_hours:
  #  - 'Monday 10:00 to 13:00'
  #  - 'Wednesday 09:00 to 10:00'
  #appointment_url: 'https://calendly.com'
  #contact_links:
  #  - icon: twitter
  #    icon_pack: fab
  #    name: DM Me
  #    link: 'https://twitter.com/Twitter'
  #  - icon: video
  #    icon_pack: fas
  #    name: Zoom Me
  #    link: 'https://zoom.com'

design:
  columns: '2'
---
