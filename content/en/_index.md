---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">ChaeHyeon PORTFOLIO</span>
      text: <br><span style="font-size:125%">Hello, I’m Chaehyeon Kim, a backend developer focused on the essentials. I thrive on continuous learning and exploration, designing robust systems while growing through problem-solving. I embrace new technologies without fear and aim to create valuable solutions by staying true to the core principles of development. Like calm but deep waters, I aspire to be a developer who adds real value with a calm demeanor and deep knowledge and experience.</span>
    
        {{% cta cta_btn="./project/" cta_text="See project →" class="" %}}



  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Profile</span>
        content: <span style="font-size:70%">Check out developer Kim Chaehyeon’s detailed information.</span>
        align: center
        background:
          image:
            filename: sky.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Profile</span>
          text-color: '#000'
          url: author/김채현

      - title: <span style="font-size:70%">Project</span>
        content: <span style="font-size:70%">Check out the projects I've done.<span style="font-size:70%">
        align: center
        background:
          image:
            filename: sky.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Project</span>
          text-color: '#000'
          url: project

      - title: <span style="font-size:70%">Plans</span>
        content: <span style="font-size:70%">Check out the interview and future projects.</span>
        align: center
        background:
          image:
            filename: sky.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Plans</span>
          text-color: '#000'
          url: futurity

      - title: <span style="font-size:70%">Information</span>
        content: <span style="font-size:70%">Check TMI, such as interests and goals.</span>
        align: center
        background:
          image:
            filename: sky.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Inform</span>
          text-color: '#000'
          url: event

      - title: <span style="font-size:70%">Contact</span>
        content: <span style="font-size:70%">Find out how you can contact us.</span>
        align: center
        background:
          image:
            filename: sky.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: user
          icon_pack: fas
          text: <span style="font-size:60%">Contact</span>
          text-color: '#000'
          url: contact


    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: features
    id: interest
    content:
      title: <span style="font-size:75%">채현's CODING Interests</span>
      text: Let me introduce my field of study and development interests that I am currently working on.<br><br><br><br>
      items:
        - name: |
            Algorithm
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">As a member of the ALPS algorithm club at the Department of Computer and Artificial Intelligence at Jeonbuk National University, I am learning algorithms through the Baekjoon platform.</span><br><br>
        - name: |
            Spring Framework
          icon: seedling
          icon_pack: fas
          description:  <span style="font-size:90%">I am currently studying the basics of the Spring framework through online courses on Inflearn.</span><br><br>
        - name: |
            Cloud Computing
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">I am exploring cloud computing, focusing on infrastructure management and service deployment, with the goal of obtaining an AWS-related certification.</span><br><br>
        - name: |
            Data Architecture
          icon: chart-line
          icon_pack: fas
          description:  <span style="font-size:90%">I am also working towards designing the data architecture for the upcoming Jeonbuk University Restaurant Project. As the first step toward achieving this goal, I am studying for the SQLD certification.</span><br><br>
        - name: |
           Development
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">I am planning a full-stack web application development project, specifically a web app for the best restaurants at Jeonbuk University.</span><br><br>
        - name: |
            Multi-modality
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">To enhance my skills as a developer, I am also studying conversational English to improve fluency.</span><br><br>


  - block: collection
    content:
      id: section-1
      title: TMI
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: futurity
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Contact me →" %}}
    design:
      columns: '1'
---