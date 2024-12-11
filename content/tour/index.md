---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: Welcome to our group's research page
        content: Take a look at what we're interested in
        align: center
        background:
          image:
            filename: #research_overview.png
            filters:
              brightness: 0.7
          position: right
          color: '#666'
#      - title: Lunch & Learn ☕️
#        content: 'Share your knowledge with the group and explore exciting new topics together!'
#        align: left
#        background:
#          image:
#            filename: contact.jpg
#            filters:
#              brightness: 0.7
#          position: center
#          color: '#555'
#      - title: World-Class Semiconductor Lab
#        content: 'Just opened last month!'
#        align: right
#        background:
#          image:
#            filename: welcome.jpg
#            filters:
#              brightness: 0.5
#          position: center
#          color: '#333'
#        link:
#          icon: graduation-cap
#          icon_pack: fas
#          text: Join Us
#          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
  - block: markdown
    content:
      title: 'ML-assisted simulations for material discovery' 
      subtitle: ''
      text: 'To overcome the limits imposed by existing resource heavy, CO2 intensive processes, we need to identify
novel materials that are more efficient. Our research group focuses on developing methods that go beyond the
status quo of exploring static properties and perform screening of the material space based on thermodynamics and
kinetics. This will enable the prediction of dynamic properties for large material spaces leading to better
identification of materials for target applications.'
    design:
      columns: '1'
      background:
        image: ''
          filename: 
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
