---
# Display name
title: 김채현

# Full Name (for SEO)
first_name: Chaehyeon
last_name: Kim

# Username (this should match the folder name)
authors:
  - admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: 백엔드 개발자

# Organizations/Affiliations
organizations:
  - name: 전북대학교 컴퓨터인공지능학부
    url: 'https://csai.jbnu.ac.kr/csai/index.do'
  

# Short bio (displayed in user profile at end of posts)
bio: 안녕하세요. 본질에 집중하는 백엔드 개발자 김채현입니다. 끊임없는 학습과 탐구로 견고한 시스템을 설계하고, 문제 해결에 집중하는 과정에서 성장을 느낍니다. 새로운 기술을 두려워하지 않고, 본질에 충실한 개발을 통해 가치 있는 솔루션을 만들어가는 것이 제 목표입니다. 잔잔하지만 깊이 있는 물처럼, 차분하면서도 깊이 있는 지식과 경험을 바탕으로 실질적인 가치를 더할 수 있는 개발자가 되겠습니다.


interests:
  - Web Services
  - API Design & Integration
  - Cloud Infrastructure
  - Development & Deploy
  - Computer Vision

education:
  courses:
    - course: B.S. in (컴퓨터공학부)
      institution: 전북대학교
      year: 2022 - 2026

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:esther107@jbnu.ac.kr'
  - icon: github
    icon_pack: fab
    link: https://github.com/chaehyeon107
  - icon: brands/x
    url: https://x.com/107daydreaming
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: 'esther107@jbnu.ac.kr'

# Highlight the author in author lists? (true/false)
highlight_name: true

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
--- 
{{ if eq .Title "김채현" }}
  <!-- hero_and_skills.css 파일을 로드 -->
  <link rel="stylesheet" href="{{ "css/hero_and_skills.css" | relURL }}">

  <!-- hero.html 템플릿을 추가 -->
  <div class="hero-section-wrapper">
    {{ partial "views/hero.html" . }}
  </div>
{{ end }}

<section class="content-section">
  {{ .Content }}
</section>

sections:
  - block: features
    id: features
    content:
      title: '채현의 CODING Interests'
      text: |
        현재 진행하고 있는 공부 분야 및 개발 관심사를 소개합니다.

      items:
        - name: 알고리즘(Algorithm)
          icon: code-branch
          icon_pack: fas
          description: |
            전북대학교 컴퓨터인공지능학부 알고리즘 동아리 ALPS 소속으로 백준 사이트에서 **알고리즘 학습 진행**.
          
        - name: spring 프레임워크 (Spring Framework)
          icon: seedling
          icon_pack: fas
          description: |
            인프런 사이트 인강을 통해 **spring 프레임워크 기초**를 학습 중.
          
        - name: 클라우드 컴퓨팅 (Cloud Computing)
          icon: calculator
          icon_pack: fas
          description: |
            인프라 관리 및 서비스 배포 등 클라우드 컴퓨팅에 관한 지식을 탐구 중. **aws 관련 자격증 취득 공부**를 목표로 함.
          
        - name: 데이터 아키텍쳐 설계 (Data Architecture)
          icon: chart-line
          icon_pack: fas
          description: |
            추후 진행할 전북대학교 맛집 프로젝트의 데이터 아키텍쳐 설계를 목표로 함. 목표를 달성하기 위한 첫 걸음으로 현재 **sqld 자격증 공부** 진행 중.
          
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description: |
            Full-Stack 기반의 응용 어플리케이션 개발. 현재 **전북대학교 맛집 웹앱 프로젝트**를 계획 중.
          
        - name: 영어회화(Multi-modality)
          icon: globe
          icon_pack: fas
          description: |
            개발자의 덕목인 영어를 자유롭게 구사하기 위해 **회화 공부** 진행.