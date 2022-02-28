---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contacto
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
  email: gonzalezhomar@gmail.com
  phone: 428 100 4700
  address:
    street: Circ. Jardín del Rey 228
    city: León
    region: Guanajuato
    postcode: '37544'
    country: México
    country_code: MX
  coordinates:
    latitude: '21.00364675985172'
    longitude: '-101.24028141735299'
  directions: Entrando en las oficinas, en el piso más elevado
  office_hours:
    - 'Lunes a viernes 10:00 to 14:00'
  #  - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: "linkedin"
      icon_pack: "fab"
      name: "LinkedIn"
      link: "https://www.linkedin.com/in/omar-humberto-gonzalez-%C3%A1vila-ab674128/"

design:
  columns: '2'
---
