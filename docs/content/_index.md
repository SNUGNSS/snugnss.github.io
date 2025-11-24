---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: hero
    id: about
    content:
      title: |
        Welcome to </br>
        **GNSS Laboratory**
      text: |-
        **Seoul National University**
        </br>
        **서울대학교 GNSS연구실**

      primary_action:
        text: SNUGLITE-III 보도자료
        url: '/snuglite/'
        # icon: hero/user-group
      secondary_action:
        text: Lab News
        url: '/news/'
        icon: hero/academic-cap
      announcement:
        text: " "
        link:
          text: "SNUGLITE-III 큐브위성의 최신 소식을 확인하세요"
          url: "/snuglite/"
    design:
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        # Option A: Modern gradient mesh (recommended for 2025/2026)
        gradient_mesh:
          enable: true
          style: "waves"
          animation: "pulse"
          intensity: "medium"
          colors:
            - "primary-500/30"
            - "black-600/20"
            - "indigo-600/15"
        
        # Option B: Team/lab image (uncomment to use instead of gradient mesh)
        # image:
        #   filename: "welcome1.jpg"
        #   filters:
        #     brightness: 0.5
        #     contrast: 1.0
        # color: '#333'

  # - block: stats
  #   content:
  #     items:
  #       - statistic: "50+"
  #         description: Publications in top-tier journals
  #         sub_metric: Nature, Science, Cell, PNAS
  #         icon: hero/document-text
  #       - statistic: "15"
  #         description: Brilliant researchers and scientists
  #         sub_metric: From 8 countries worldwide
  #         icon: hero/user-group
  #       - statistic: "$5M"
  #         description: Active research funding
  #         sub_metric: NSF, NIH, DOE grants
  #         icon: hero/currency-dollar
  #       - statistic: "12"
  #         description: Active research projects
  #         sub_metric: Across 3 major domains
  #         icon: hero/beaker
  #   design:
  #     layout: cards
  #     # Section background color (CSS class)
  #     css_class: "bg-gradient-to-b from-primary-50 to-white dark:from-primary-900/20 dark:to-gray-800"
  #     spacing:
  #       padding: ["3rem", 0, "3rem", 0]

  - block: research-areas
    content:
      title: Research
      subtitle: ''
      # text: Our lab conducts cutting-edge research across multiple domains, combining computational methods with experimental validation
      columns: 2
      items:
        - name: SNUGLITE CubeSat
          description: ''
          image: welcome1.jpg
          # icon: hero/beaker
          # gradient: from-green-400 to-emerald-600
          # status: active
          topics:
            - Spacecraft Attitude Orbit Control System (ADCS, AOCS)
            - GPS Attitude Determination
            - GPS Relative Navigation
          # team_size: 12
          # publications: 45+
          # funding: $2.5M NSF/NIH
          cta:
            text: Explore Projects
            url: /snuglite/
            
        - name: Satellite Navigation System (GPS/GNSS)
          description: ''
          image: welcome2.jpg
          # icon: hero/cpu-chip
          # gradient: from-purple-400 to-pink-600
          # status: active
          topics:
            - GNSS Receiver           
            - GNSS Orbit Determination
          # team_size: 8
          # publications: 32+
          # funding: $1.8M NSF
          # cta:
          #   text: View Research
          #   url: /research/machine-learning  
          
        - name: Satellite Augmentation System
          description: ''
          image: welcome2.jpg
          topics:
            - SBAS, DGPS, WADGPS, WASS
            - Real-Time Kinematic (Compact Network RTK)
            
        - name: Pseudolite (Indoor Navigation System)
          description: ''
          image: welcome2.jpg

        # - name: Avionics
        #   description: ''
        #   image: welcome2.jpg
        

    design:
      layout: cards
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
      spacing:
        padding: ["5rem", 0, "5rem", 0]
      columns: 2

  # - block: cta-image-paragraph
  #   content:
  #     items:
  #       - title: 'SNUGLITE-III CubeSat'
  #         text: ''
  #         image: welcome1.jpg
  #         feature_icon: hero/check-circle
  #         features:
  #           - 'High-Performance Computing: 500+ core GPU cluster for AI/ML research'
  #           - 'Advanced Instrumentation: Precision equipment for materials characterization'
  #           - 'Safety & Compliance: Full safety protocols and regulatory compliance'
  #         button:
  #           text: 'Virtual Lab Tour'
  #           url: '/facilities'

  #       - title: 'Collaborative Innovation Culture' 
  #         text: |
  #           Breakthrough research happens through collaboration. Our open lab environment fosters cross-disciplinary partnerships, knowledge sharing, and mentorship between senior researchers and emerging scientists. Every team member contributes to our collective mission of advancing scientific understanding.
  #         image: pexels-canvastudio-3153198.jpg
  #         feature_icon: hero/users
  #         features:
  #           - 'Cross-Disciplinary Teams: Biologists, engineers, and computer scientists working together'
  #           - 'Knowledge Sharing: Weekly seminars and collaborative research meetings'
  #           - 'Mentorship Program: Structured guidance for PhD students and postdocs'
  #         button:
  #           text: 'Join Our Community'
  #           url: '/opportunities'
    # design:
    #   css_class: "bg-white dark:bg-gray-800"
    #   spacing:
    #     padding: ["4rem", 0, "4rem", 0]

  # - block: collection
  #   id: projects
  #   content:
  #     title: Active Research Projects
  #     subtitle: ''
  #     text: ''
  #     filters:
  #       folders:
  #         - projects
  #     count: 0  # Number of items to show (0 = all)
  #     # Default filter UI (for future release)
  #     #default_button_index: 0
  #     # Filter toolbar (optional)
  #     # Add or remove as many filters as you like
  #   #   buttons:
  #   #     - name: All
  #   #       tag: '*'
  #   #     - name: Machine Learning
  #   #       tag: ML
  #   #     - name: Biology
  #   #       tag: Biology
  #   #     - name: Materials
  #   #       tag: Materials
  #   design:
  #     view: article-grid
  #     columns: 2

  - block: collection
    id: events
    content:
      title: Lab News
      subtitle: '최신 보도자료'
      text: ''
      filters:
        folders:
          - news
      count: 2  # Number of items to show (0 = all)
      # Default filter UI (for future release)
      #default_button_index: 0
      # Filter toolbar (optional)
      # Add or remove as many filters as you like
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Machine Learning
    #       tag: ML
    #     - name: Biology
    #       tag: Biology
    #     - name: Materials
    #       tag: Materials
    design:
      view: article-grid
      columns: 2

  # - block: logos
  #   content:
  #     title: Lab Partners
  #     subtitle: ''
  #     text: ''''
  #     logos:
  #       - name: SNU
  #         image: partners/snu.png
  #         url: https://snu.ac.kr
  #         external: true
  #         description: Seoul National University
  #   design:
  #     display_mode: grid
  #     show_pattern: false
  #     css_class: "bg-gradient-to-b from-white to-gray-50 dark:from-gray-800 dark:to-gray-900"
  #     spacing:
  #       padding: ["4rem", 0, "4rem", 0]

  - block: contact-info
    id: id-contact
    content:
      title: Contact Us
      # subtitle: Get in touch with our research team
      visit_title: Visit Our Lab
      connect_title: Connect With Us
      address:
        lines:
          - GNSS Laboratory
          - Build#312, Room#501, 
          - Seoul National University
          - Seoul, Korea
          - 정밀기계설계공동연구소 312동 501호
          - 서울시 관악구 관악로 1 서울대학교 
          - 대한민국
      email: snugnss@gmail.com
      # phone: "+1 (555) 123-4567"
      map_url: https://maps.google.com/?q=서울대학교+312동
    design:
      css_class: "bg-gradient-to-b from-gray-50 to-white dark:from-gray-900 dark:to-gray-800"
      spacing:
        padding: ["5rem", 0, "5rem", 0]

  # - block: hero
  #   content:
  #     text: |
  #       <p style="font-size:18px;">
  #       Introducing our GNSS & CubeSat research <br>
  #       <img src="logo.png" alt="SNU Logo" width="70" style="margin-top:8px; vertical-align:middle;">
  #       </p>

---