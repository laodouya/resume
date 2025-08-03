---
# Display name
title: "Xu Jin"

# Name pronunciation (optional)
name_pronunciation: ""

# Full name (for SEO)
first_name: "Xu"
last_name: "Jin"

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: "Senior Software Architect & Platform Lead"

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: "GDDI Innovation Technology Co., Ltd."
    url: ""

# Short bio (displayed in user profile at end of posts)
bio: "11+ years experience in Go, Python, and distributed systems architecture. Specialized in AI platforms, microservices, and enterprise solutions."

# Social Networking
social:
  - icon: envelope
    icon_pack: fas
    link: 'mailto:job@laodouya.com'
  - icon: github
    icon_pack: fab
    link: https://github.com/laodouya
  - icon: phone
    icon_pack: fas
    link: 'tel:+8615810540933'

# Interests
interests:
  - Distributed Systems Architecture
  - AI/ML Platform Development
  - Microservices & Cloud Native
  - DevOps & Infrastructure
  - Open Source Projects

# Education
education:
  courses:
    - course: "Master of Software Engineering"
      institution: "Beijing Jiaotong University"
      year: "2014"
      details: |
        - Internships: Tencent (Nov 2011 – Aug 2012), Baidu (Apr 2013 – Sep 2013)
    - course: "Bachelor of Software Engineering"
      institution: "Beihang University"
      year: "2011"
      details: |
        - Awards: Second-Class Scholarship; 2nd Prize, Microsoft Imagination Cup; SRTP (Student Research Training Program)

# Skills
skills:
  - name: "Programming Languages"
    items:
      - name: "Go"
        description: "9+ years experience"
        percent: 95
      - name: "Python"
        description: "4+ years experience"
        percent: 85
      - name: "C/SQL"
        description: "Proficient"
        percent: 80

  - name: "Backend & Infrastructure"
    items:
      - name: "Kubernetes"
        description: "Container orchestration, custom CRDs"
        percent: 90
      - name: "Microservices"
        description: "Gin, Beego, gRPC, Protobuf"
        percent: 95
      - name: "DevOps"
        description: "GitLab CI, ArgoCD, Docker, Harbor"
        percent: 88

  - name: "Data & Messaging"
    items:
      - name: "Databases"
        description: "PostgreSQL, MySQL, MongoDB, Redis, ClickHouse"
        percent: 85
      - name: "Message Queues"
        description: "Kafka, RabbitMQ, APISIX"
        percent: 80
      - name: "Monitoring"
        description: "Prometheus, logging systems"
        percent: 75

# Work Experience
experience:
  - title: "Head of Software Platform, Architect"
    company: "GDDI Innovation Technology Co., Ltd."
    company_url: ""
    company_logo: ""
    location: "Shenzhen, China"
    date_start: "2023-10-01"
    date_end: ""
    description: |
      Leading architecture and development of dual AI platforms (training + annotation) serving 20+ enterprise customers.
      
      **Key Achievements:**
      - Architected microservices platform using Go, Kubernetes, and custom CRDs for AI training workflows
      - Developed GPU scheduling middleware with custom nvidia-k8s-plugin for optimized workload allocation  
      - Built comprehensive offline licensing system supporting multiple authorization modes
      - Established CI/CD pipeline with ArgoCD, automated testing framework, and quality assurance processes
      - Successfully deployed to 20+ enterprise customers with complex multi-GPU configurations

  - title: "System Architect, InfoSec Department"
    company: "Xunlei Limited"
    company_url: ""
    company_logo: ""
    location: "Shenzhen, China"
    date_start: "2020-04-01"
    date_end: "2023-06-01"
    description: |
      Built and scaled commercial SaaS platform generating ¥500K monthly revenue with 20+ enterprise clients.
      
      **Key Achievements:**
      - Architected multi-tenant SaaS platform with RBAC, billing, and automated account management
      - Improved reviewer accuracy from 88% to 98% and reduced wait time from 15 to 2 minutes
      - Developed multilingual SDKs with RSA encryption for 20+ enterprise client integrations
      - Built AI model service pipeline, reducing GPU pressure by 80% through optimization strategies
      - Implemented comprehensive security measures including encrypted communications and financial transaction systems

  - title: "Tech Manager"
    company: "Shanxian Daojia Grocery App"
    company_url: ""
    company_logo: ""
    location: "China"
    date_start: "2019-11-01"
    date_end: "2020-04-01"
    description: |
      Built complete backend infrastructure from scratch, leading 6-member development team.
      
      **Key Achievements:**
      - Architected scalable microservices for SKU management, payment integration, and delivery logistics
      - Implemented WeChat/Alipay payment integration and rider dispatch algorithms
      - Led cross-functional team coordination and technical project management

  - title: "Core Developer"
    company: "CovenantSQL (Open Source Blockchain Database)"
    company_url: ""
    company_logo: ""
    location: "Remote"
    date_start: "2018-05-01"
    date_end: "2019-11-01"
    description: |
      Core contributor to decentralized SQL database with 1.5k+ GitHub stars.
      
      **Key Achievements:**
      - Architected two-layer blockchain structure with main chain settlement and sub-chain storage
      - Developed comprehensive SDK ecosystem: CLI tools, Python/Java drivers, and client libraries
      - Built GNTE network simulation tool that reached GitHub Trending
      - Conducted distributed consistency testing and performance benchmarking

  - title: "Infrastructure Engineer"
    company: "Meitu Inc."
    company_url: ""
    company_logo: ""
    location: "Shenzhen, China"
    date_start: "2016-01-01"
    date_end: "2018-04-01"
    description: |
      Developed core infrastructure libraries and supported live streaming platform.
      
      **Key Achievements:**
      - Developed Go libraries for Etcd operations, logging, and standardized storage formats
      - Built RTMP transcoding services using FFmpeg optimization for live streaming
      - Provided architectural consulting and technology research for product teams

  - title: "Backend Developer"
    company: "Xunlei Limited"
    company_url: ""
    company_logo: ""
    location: "China"
    date_start: "2014-07-01"
    date_end: "2015-10-01"
    description: |
      Developed high-performance P2P services and CDN infrastructure.
      
      **Key Achievements:**
      - Built BT-Box torrent indexing service for P2P content discovery
      - Developed distributed CDN client based on Nginx architecture
      - Implemented backend services for membership and content distribution

# Projects
projects:
  - title: "chDB (Python Library)"
    url: ""
    summary: "Active contributor to chDB-io project enabling SQL-like queries on flat files (CSV, Parquet) directly in Python, based on ClickHouse engine."
    tags:
      - "Python"
      - "SQL"
      - "Analytics"
      - "Open Source"

  - title: "CovenantSQL"
    url: ""
    summary: "Major contributor to open-source blockchain database project (1.5k+ GitHub stars). Developed multiple SDK implementations and tooling ecosystem."
    tags:
      - "Blockchain"
      - "Database"
      - "Go"
      - "Distributed Systems"

  - title: "GNTE (Global Network Topology Emulator)"
    url: ""
    summary: "Created network simulation tool that reached GitHub Trending. Used for distributed system testing and network latency simulation."
    tags:
      - "Network Simulation"
      - "Distributed Testing"
      - "Go"

# Contact details
address:
  street: ""
  city: "Shenzhen"
  region: "Guangdong"
  postcode: ""
  country: "China"

coordinates:
  latitude: "22.5431"
  longitude: "114.0579"

phone: "+86 15810540933"
email: "job@laodouya.com"
---

Senior Software Architect and Platform Lead with 11+ years of experience specializing in distributed systems, AI/ML platforms, and enterprise-grade solutions. Proven track record of architecting and scaling systems serving millions of users and generating significant revenue.

## Expertise Highlights

**AI & ML Platforms**: Architected comprehensive AI training and annotation platforms with custom Kubernetes orchestration, GPU optimization, and SOTA model integration.

**Enterprise Solutions**: Built multi-tenant SaaS platforms serving 20+ enterprise clients with complex billing, authentication, and compliance requirements.

**Distributed Systems**: Extensive experience with microservices architecture, message queues, distributed databases, and high-availability systems.

**DevOps & Infrastructure**: Expert in Kubernetes, Docker, CI/CD pipelines, monitoring systems, and automated deployment strategies.

**Open Source Leadership**: Core contributor to blockchain database projects with 1.5k+ GitHub stars and multiple SDK implementations.

Currently leading platform architecture at GDDI Innovation Technology, focusing on AI training infrastructure and enterprise deployment solutions.