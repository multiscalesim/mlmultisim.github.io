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
      title: ML-assisted simulations for material discovery
      subtitle: ''
      text: To overcome the limits imposed by existing resource heavy, CO2 intensive processes, we need to identify
            novel materials that are more efficient. Our research group focuses on developing methods that go beyond the
            status quo of exploring static properties and perform screening of the material space based on thermodynamics and
            kinetics. This will enable the prediction of dynamic properties for large material spaces leading to better
            identification of materials for target applications.
    design:
      columns: '1'
  - block: markdown
    content:
      title: Predictive and quantitative multi-scale modeling
      subtitle: ''
      text: Finding more efficient manufacturing processes and finding alternate
            manufacturing processes using electricity as two of the key targets to achieve a net-zero carbon emission by 2050.
            To achieve the emission target, we need to concurrently focus on understanding the basic science behind these alternate 
            processes while making them technology ready. Our group adopts a bottoms up approach when approaching
            these research problems. Quantum chemistry calculations and molecular dynamics simulations provide the essential
            atomistic understanding of the fundamental chemistry. The insights gained from the atomistic perspectives such as
            rate constants can then be applied to device scale simulations. Our bottoms up approach allows us to perform
            predictive and quantitative modeling of the non-equilibrium and dynamic processes.
    design:
      columns: '1'
---
