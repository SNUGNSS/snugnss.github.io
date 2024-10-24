---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: <strong>SNUGLITE CubeSat</strong>
        content: 
          Seoul National University
          </br>
          </br>
          
        align: center
        background:
          image:
            filename: welcome1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          # icon: graduation-cap
          # icon_pack: fas
          text: <strong>보도자료</strong>
          url: event/

      - title: <strong>Differential GPS</strong>
        content: |-

          </br>
          </br>
          WADGPS is an acronym for Wide Area Differential GPS. It's a general term for solutions used to enhance GPS accuracy, availability and integrity over large areas. A WADGPS uses a state-based approach in their software architecture. This means that a separate correction is made available for each error source rather than the sum effect of errors on the user equipment’s range measurements. This more effectively manages the issue of spatial decorrelation than some other techniques, resulting in a more consistent system performance regardless of geographic location with respect to reference stations.
          
          
        align: center
        background:
          image:
            filename: welcome2.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 10000
---
