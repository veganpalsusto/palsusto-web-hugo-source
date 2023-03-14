---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '400px'
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to our bakery! 
      content: Thank you for your visit! 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome-buy-vegan-conchas-in-london-and-uk.jpg
      link:
        icon: instagram
        icon_pack: fab
        text: Follow us
        url: 'https://www.instagram.com/vegan.palsusto'

    - title: Order from us vegan conchas (and soon more!)
      content: Learn how 
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: coffee-with-vegan-conchas-uk.jpg
      link:
        icon: envelope
        icon_pack: fas
        text: Contact Us
        url: ../contact/

    - title: Check Our Menu
      content: 'Learn About Ingredients and Allergens!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: contact-us-for-vegan-conchas-in-the-uk.jpg
      link:
        icon: utensils
        icon_pack: fas
        text: Menu 
        url: ../menu/
---
