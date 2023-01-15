---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '300px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Menu
      content: Take a look at what we're baking...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome.jpg
      link:
        icon: envelope
        icon_pack: fas
        text: How to order
        url: ../how-to-order/
    - title: Classics 
      content: 'We sell classic cocoa and vanilla conchas...'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: coffee.jpg
    - title: Limited Edition
      content: '...or Limited Edition with specialised designs and colours'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: coders.jpg
      # link:
      #   icon: graduation-cap
      #   icon_pack: fas
      #   text: Join Us
      #   url: ../contact/
---
