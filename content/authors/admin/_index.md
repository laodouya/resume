---
# Display name
title: Xu Jin

# Name pronunciation (optional)
name_pronunciation: ""

# Full name (for SEO)
first_name: Xu
last_name: Jin

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Senior Software Architect & Platform Lead

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: GDDI Innovation Technology Co., Ltd.
    url: ""

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:job@laodouya.com'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/laodouya
    label: GitHub
  - icon: phone
    url: 'tel:+8615810540933'
    label: Call Me

education:
  - area: Master of Software Engineering
    institution: Beijing Jiaotong University
    date_start: 2011-09-01
    date_end: 2014-07-01
    summary: |
      **Internships:** Tencent (Nov 2011 – Aug 2012), Baidu (Apr 2013 – Sep 2013)
  - area: Bachelor of Software Engineering
    institution: Beihang University
    date_start: 2007-09-01
    date_end: 2011-07-01
    summary: |
      **Awards:** Second-Class Scholarship; 2nd Prize, Microsoft Imagination Cup; SRTP (Student Research Training Program)

work:
  - position: Head of Software Platform, Architect
    company_name: GDDI Innovation Technology Co., Ltd.
    company_url: 'https://www.gddi.com.cn'
    company_logo: ''
    date_start: 2023-10-01
    date_end: ''
    summary: |2-
      Leading architecture and development of dual AI platforms (training + annotation) serving 20+ enterprise customers.

      **AI Training & Annotation Platform Architecture:**
      - Architected complete redesign using microservices with Go (Gin/Beego/Gorm), Protobuf, and Kubernetes
      - Built custom Kubernetes scheduling middleware with nvidia-k8s-plugin for GPU optimization
      - Developed custom resource definitions (CRDs) for multi-pod task management

      **Enterprise Deployment & Licensing:**
      - Successfully deployed to 20+ enterprise customers with complex multi-GPU configurations
      - Designed comprehensive offline licensing system with year/device/model/video-stream authorization
      - Integrated custom SSO solutions and provided hardware consultation

      **Engineering Leadership:**
      - Established comprehensive CI testing framework and ArgoCD-based deployment system
      - Led cross-functional team (backend/frontend/QA/DevOps) coordination
  - position: System Architect, InfoSec Department
    company_name: Xunlei Limited
    company_url: 'https://www.xunlei.com'
    company_logo: ''
    date_start: 2020-04-01
    date_end: 2023-06-01
    summary: |2-
      Built and scaled commercial SaaS platform generating ¥500K monthly revenue with 20+ enterprise clients.

      **Commercial SaaS Platform:**
      - Architected multi-tenant platform with RBAC permissions, billing, and account management
      - Built microservices using Go-Gin, PostgreSQL/GORM, Redis, Kafka, RabbitMQ, Etcd
      - Implemented APISIX gateway plugins for authentication and service routing

      **Performance & Quality Improvements:**
      - Improved reviewer accuracy from 88% to 98% and reduced wait time from 15min to 2min
      - Redesigned task assignment workflow with state machine control
      - Added comprehensive Prometheus monitoring for performance optimization

      **SDK Development & Client Integration:**
      - Developed multilingual SDKs with RSA encryption for 20+ enterprise clients
      - Successfully deployed and conducted integration testing for 10+ production clients
  - position: Tech Manager
    company_name: Shanxian Daojia Grocery App
    company_url: ''
    company_logo: ''
    date_start: 2019-11-01
    date_end: 2020-04-01
    summary: |2-
      Built complete backend infrastructure from scratch using Go, leading a 6-member team.

      **Core Infrastructure:**
      - Architected and implemented SKU management, WeChat/Alipay payment integration
      - Developed rider dispatch algorithms, billing system, and promotional coupon engine
      - Designed scalable microservices architecture for real-time order processing
  - position: Core Developer
    company_name: CovenantSQL (Open Source Blockchain Database)
    company_url: 'https://github.com/CovenantSQL/CovenantSQL'
    company_logo: ''
    date_start: 2018-05-01
    date_end: 2019-11-01
    summary: |2-
      Core contributor to decentralized SQL database with blockchain characteristics (1.5k+ GitHub stars).

      **Architecture & Development:**
      - Architected two-layer structure with main chain settlement and sub-chain storage
      - Developed comprehensive SDK ecosystem: CQL CLI tool, Python-driver, Java-driver
      - Built GNTE (Global Network Topology Emulator) that reached GitHub Trending
      - Conducted distributed linear consistency testing and performance benchmarking
  - position: Infrastructure Engineer
    company_name: Meitu Inc.
    company_url: 'https://www.meitu.com'
    company_logo: ''
    date_start: 2016-01-01
    date_end: 2018-04-01
    summary: |2-
      Developed core infrastructure libraries and supported live streaming platform.

      **Infrastructure Development:**
      - Developed Go libraries: Etcd wrapper, comprehensive logging library
      - Built RTMP transcoding services using FFmpeg optimization
      - Spearheaded adoption of Git workflows, Go dependency management, and CI processes
  - position: Backend Developer
    company_name: Xunlei Limited
    company_url: 'https://www.xunlei.com'
    company_logo: ''
    date_start: 2014-07-01
    date_end: 2015-10-01
    summary: |2-
      Developed high-performance P2P services and CDN infrastructure.

      **P2P & CDN Systems:**
      - Built BT-Box torrent indexing service for content discovery
      - Developed distributed CDN client based on Nginx architecture
      - Implemented backend services for membership and content distribution

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Programming Languages
    items:
      - name: Go
        description: '9+ years experience in microservices, distributed systems'
        percent: 95
        icon: devicon/go
      - name: Python
        description: '4+ years in AI/ML integration, automation'
        percent: 85
        icon: devicon/python
      - name: C/SQL
        description: 'Systems programming and database design'
        percent: 80
        icon: devicon/c
  - name: Infrastructure & Cloud
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Kubernetes
        description: 'Container orchestration, custom CRDs, GPU scheduling'
        percent: 90
        icon: devicon/kubernetes
      - name: Docker & CI/CD
        description: 'GitLab CI, ArgoCD, Harbor, automated deployment'
        percent: 88
        icon: devicon/docker
      - name: Databases
        description: 'PostgreSQL, MySQL, MongoDB, Redis, ClickHouse'
        percent: 85
        icon: devicon/postgresql

languages:
  - name: English
    percent: 85
  - name: Chinese
    percent: 100
---

Senior Software Architect with **11+ years of experience** specializing in distributed systems, AI/ML platforms, and enterprise solutions. Currently serving as **Head of Software Platform** at GDDI Innovation Technology, focusing on AI training infrastructure and enterprise deployment solutions.

**Core Expertise:** Go (9+ years), Python (4+ years), Kubernetes, microservices architecture, and AI platform development.

**Notable Achievements:** Core contributor to CovenantSQL blockchain database project (1.5k+ GitHub stars) and creator of GNTE network simulation tool that reached GitHub Trending.