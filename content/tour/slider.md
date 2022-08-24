---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Delivery dates
      content: Take a look on Instagram
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
      link:
        icon: instagram
        icon_pack: fab
        text: Go to Instagram
        url: www.instagram.com/vegan.palsusto

    - title: Message us your order
      content: 'via Instagram DM or email'
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg

      link:
        icon: envelope
        icon_pack: fas
        text: Contact Us
        url: ../contact/

    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
