---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: Open for Orders!
  #     image:
  #       filename: orders.png
  #     text: |-
  #       <br> 

  #       **The Future Market** from 12th-14th July 

  #       {{% cta cta_link="./event/" cta_text="More info here!" %}}

  #       Normal online orders: **July date** is open for receiving orders. Do not miss out on yours. 
        
  #       **London Collection:** July 23rd

  #       **UK Delivery:** July 24th


  #       <br>

  #       {{% cta cta_link="./contact/" cta_text="Contact page →" %}}
  #   design:
  #     background:
  #       gradient_end: '#ECE3DF' #'#607D78' # '#7C5A50'
  #       gradient_start: '#A9C9C4' # '#AACCC3'
  #       text_color_light: false

  - block: hero
    content:
      title: Pa'l Susto Vegan Bakery
      image:
        filename: welcome2.jpg
      text: |
        <br>
        
        Introducing the UK's first vegan Mexican micro bakery, crafting authentic pan dulce (sweet bread). Discover vegan award-winning Conchas, Marranitos, Pan de Muerto, and Rosca de Reyes, reimagined for vegan indulgence. Vegan conchas are our speciality. 

  - block: markdown
    content:
      title: 'About us'
      subtitle: 
      text: | 
        <br>

        Our mission is to share Mexican baked goods with the UK, which are also **vegan-friendly**! 

        Founded by a passionate vegan couple, our online bakery offers monthly UK postal and London collection. Also available for large events or custom orders. Enjoy the richness of Mexican flavours, crafted without animal products.

        <!-- _My Mexican husband misses all things Mexican & there isn’t a place selling vegan pan dulce like   **conchas** or festive bakes like **Pan de Muerto** & **Rosca de Reyes**!_ -->

        If you’ve never tried Mexican Pan Dulce, order some & give it a try with coffee, hot chocolate or a glass of (plant-based) milk.
        
    design:
      columns: '2'
  
  - block: collection
    content:
      title: Pop-ups & Events
      subtitle: Upcoming pop-ups and events!
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: 2
      columns: '2'

  - block: collection
    content:
      title: Latest News
      subtitle: 
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: 2
      columns: '2'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: vegan-concha-custom-2.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./menu/" cta_text="Check our menu →" %}}
    design:
      columns: '1'
---