---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: <span style="font-size:70%">ChaeHyeon PORTFOLIO</span>
      text: <br><span style="font-size:125%">안녕하세요. 본질에 집중하는 백엔드 개발자 김채현입니다.<br><br>현재 전북대학교 컴퓨터공학부에 재학 중입니다. 다양한 프로젝트와 학습을 통해 새로운 기술을 두려워하지 않고, 본질에 충실한 개발을 통해 가치 있는 솔루션을 만들어가는 것이 제 목표입니다. 잔잔하지만 깊이 있는 물처럼, 차분하면서도 깊이 있는 지식과 경험을 바탕으로 실질적인 가치를 더할 수 있는 개발자가 되겠습니다.</span>
    
        {{% cta cta_link="./project/" cta_text="project 보러가기 →" %}}


  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Profile</span>
        content: <span style="font-size:70%">김채현 개발자의 상세한 정보를 확인합니다.</span>
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
        content: <span style="font-size:70%">수행한 프로젝트를 확인합니다.<span style="font-size:70%">
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
        content: <span style="font-size:70%">인터뷰와 미래에 만들어질 프로젝트를 확인합니다.</span>
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
        content: <span style="font-size:70%">관심사와 목표 등 TMI를 확인합니다.</span>
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
        content: <span style="font-size:70%">연락할 수 있는 방안을 확인합니다.</span>
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
      page_type: publication
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