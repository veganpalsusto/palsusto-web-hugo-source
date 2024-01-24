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
        media: welcome-buy-vegan-conchas-in-london-and-uk.jpg
      link:
        icon: envelope
        icon_pack: fas
        text: How to order
        url: ../how-to-order/
    - title: Custom Orders
      content: Want something special, specific, or order a large amount?
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.7 
        media: vegan-concha-custom-2.jpg
      link:
        icon: star
        icon_pack: fas
        text: Let us help
        url: ../custom-orders/
    - title: Classics 
      content: 'We sell classic cocoa and vanilla vegan conchas...'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: coffee-with-vegan-conchas-uk.jpg
    - title: Limited Edition
      content: '...or Limited Edition with specialised designs and colours'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: vegan-concha-uk-limited.jpg
      # link:
      #   icon: graduation-cap
      #   icon_pack: fas
      #   text: Join Us
      #   url: ../contact/
---
