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
        content: |-
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
          url: snuglite/

      - title: <strong>Wide Area Differential GPS</strong>
        content: |-
          
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

  - block: collection
    content:
      title: Latest News
      text: ""
      count: 3
      filters:
        folders: 
          - event
        featured_only: false
        order: desc  # 최신 포스트를 우선 표시
    design:
      view: compact
      columns: '2'

---
