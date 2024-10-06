---
# Leave the homepage title empty to use the site title
title: "about"
date: 2024-10-01
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
    
    design:
      background:
        color: #FFFFFF

  - block: markdown
    content:
        title: bio
        text: |- 
          <span class="justified-text">
          Hello, I’m Chaehyeon Kim, a backend developer focused on the essentials. I thrive on continuous learning and exploration, designing robust systems while growing through problem-solving. I embrace new technologies without fear and aim to create valuable solutions by staying true to the core principles of development. Like calm but deep waters, I aspire to be a developer who adds real value with a calm demeanor and deep knowledge and experience.</span>
      
  - block: interest
    content:
      title: 'ChaeHyeon’s CODING Interests'
      items:
        - name: Algorithm
          description: |
            As a member of the ALPS algorithm club at the Department of Computer and Artificial Intelligence at Jeonbuk National University, I am **learning algorithms** through the Baekjoon platform.
          icon: code-branch
          icon_pack: fas
        - name: Spring Framework
          description: |
            I am currently studying the **basics of the Spring framework** through online courses on Inflearn.
          icon: seedling
          icon_pack: fas
        - name: Cloud Computing
          description: |
            I am exploring cloud computing, focusing on infrastructure management and service deployment, with the goal of obtaining **an AWS-related certification**.
          icon: calculator
          icon_pack: fas
        - name: Data Architecture
          description: |
            I am also working towards designing the data architecture for the upcoming Jeonbuk University Restaurant Project. As the first step toward achieving this goal, I am studying for the **SQLD certification**.
          icon: chart-line
          icon_pack: fas
        - name: Development
          description: |
            I am planning a full-stack web application development project, specifically a web app for **the best restaurants at Jeonbuk University**.
          icon: laptop
          icon_pack: fas
        - name: English conversation
          description: |
            To enhance my skills as a developer, I am also studying **conversational English** to improve fluency.
          icon: globe
          icon_pack: fas
    design:
      columns: 1
      
  - block: techstack
    content:
      title: 'Tech Stack'
      items:
        - name: Backend
          items:
            - name: Kotlin
            - name: Java
            - name: Spring Boot
            - name: Spring
            - name: Gradle
        - name: DevOps
          items:
            - name: AWS - EC2
            - name: MySQL
            - name: Markdown
        - name: Frontend
          items:
            - name: HTML
            - name: CSS
            - name: JS
        - name: Tools & Collaboration
          items:
            - name: Git
            - name: Jira
            - name: Slack
            - name: VS Code
            - name: Intellij
            - name: Pycharm
            - name: Eclipse
            - name: Android Studio
    design:
      columns: 1
---