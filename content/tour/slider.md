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
        text: Follow us for updates
        url: 'https://www.instagram.com/vegan.palsusto'

    - title: Order from us vegan conchas (and more!)
      content: Learn how 
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: vegan-concha-custom-2.jpg
      link:
        icon: shop
        icon_pack: fas
        text: See what's available!
        url: https://veganpalsusto.square.site/s/order?shipping=true#WOFXTM4FNJUY2B5DB4F3BX7F

    - title: Check Our Menu
      content: 'Learn About Ingredients and Allergens!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: vegan-concha-rosca.jpg
      link:
        icon: utensils
        icon_pack: fas
        text: Menu 
        url: ../menu/
---
