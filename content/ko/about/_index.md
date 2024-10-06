---
# Leave the homepage title empty to use the site title
title: "about"
date: 2024-10-01
type: landing
draft: false

first_name: ChaeHyeon
last_name: Kim

sections:

  - block: about.biography
    id: about
    content:
      title: ''
      username: admin

  - block: markdown
    content:
        title: bio
        text: |
          <span class="justified-text">
          안녕하세요. 본질에 집중하는 백엔드 개발자 김채현입니다.<br><br>현재 전북대학교 컴퓨터공학부에 재학 중입니다. 다양한 프로젝트와 학습을 통해 새로운 기술을 두려워하지 않고, 본질에 충실한 개발을 통해 가치 있는 솔루션을 만들어가는 것이 제 목표입니다. 잔잔하지만 깊이 있는 물처럼, 차분하면서도 깊이 있는 지식과 경험을 바탕으로 실질적인 가치를 더할 수 있는 개발자가 되겠습니다. </span>
      
  - block: features
    id: interesting1
    content:
      title: <span style="font-size:75%">채현's CODING Interests</span>
      text: 현재 진행하고 있는 공부 분야 및 개발 관심사를 소개합니다.<br><br><br><br>
      items:
        - name: |
            알고리즘
            (Algorithm)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">전북대학교 컴퓨터인공지능학부 알고리즘 동아리 ALPS 소속으로 백준 사이트에서 알고리즘 학습 진행.</span><br><br>
        - name: |
            spring 프레임워크 
            (Spring Framework)
          icon: seedling
          icon_pack: fas
          description:  <span style="font-size:90%">인프런 사이트 인강을 통해 spring 프레임워크 기초를 학습 중.</span><br><br>
        - name: |
            클라우드 컴퓨팅
            (Cloud Computing)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">인프라 관리 및 서비스 배포 등 클라우드 컴퓨팅에 관한 지식을 탐구 중. aws 관련 자격증 취득 공부를 목표로 함.</span><br><br>
        - name: |
            데이터 아키텍쳐 설계
            (Data Architecture)
          icon: chart-line
          icon_pack: fas
          description:  <span style="font-size:90%">추후 진행할 전북대학교 맛집 프로젝트의 데이터 아키텍쳐 설계를 목표로 함. 목표를 달성하기 위한 첫 걸음으로 현재 sqld 자격증 공부 진행 중.</span><br><br>
        - name: |
           개발
           (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발. 현재 전북대학교 맛집 웹앱 프로젝트를 계획 중.</span><br><br>
        - name: |
            영어회화
            (Multi-modality)
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">개발자의 덕목인 영어를 자유롭게 구사하기 위해 회화 공부 진행.</span><br><br>
    design:
      columns: 2
      
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
      columns: 2

---