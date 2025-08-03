---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: "Xu Jin"
      text: |
        **Senior Software Architect & Platform Lead**
        
        11+ years experience in Go, Python, and distributed systems architecture. 
        Specialized in AI platforms, microservices, and enterprise solutions.
        
        📍 **Location:** Shenzhen, China  
        💼 **Experience:** 11 Years | **Languages:** Go (9 years), Python (4 years)  
        📧 **Email:** [job@laodouya.com](mailto:job@laodouya.com)  
        🔗 **GitHub:** [github.com/laodouya](https://github.com/laodouya)  
        📱 **Phone:** +86 15810540933
      primary_action:
        text: "Download Resume"
        url: "uploads/resume.pdf"
      secondary_action:
        text: "Contact Me"
        url: "mailto:job@laodouya.com"
    design:
      spacing:
        padding: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"

  - block: markdown
    content:
      title: "Professional Experience"
      text: |
        ## Current Position
        
        ### GDDI Innovation Technology Co., Ltd. — Shenzhen
        **Head of Software Platform, Architect** | *Oct 2023 – Present*
        - Architected and led complete redesign of dual AI platforms (training + annotation) using microservices
        - Built custom Kubernetes scheduling middleware and customized nvidia-k8s-plugin
        - Successfully deployed to 20+ enterprise customers with complex multi-GPU configurations
        - Established comprehensive CI testing framework and ArgoCD-based deployment system
        
        ## Previous Experience
        
        ### Xunlei Limited — Shenzhen
        **System Architect, InfoSec Department** | *Apr 2020 – Jun 2023*
        - Architected enterprise SaaS platform serving 20+ clients with ~¥500K monthly revenue
        - Improved reviewer accuracy from 88% to 98% and reduced average wait time from 15 minutes to 2 minutes
        - Developed multilingual SDKs with RSA encryption for 20+ enterprise client integrations
        
        ### CovenantSQL (Open Source Blockchain Database)
        **Core Developer** | *May 2018 – Nov 2019*
        - Core contributor to decentralized SQL database with blockchain characteristics (1.5k+ GitHub stars)
        - Built GNTE network simulation tool that reached GitHub Trending
        - Developed comprehensive SDK ecosystem: CLI tools, Python/Java drivers
        
        ### Previous Roles
        - **Tech Manager** at Shanxian Daojia Grocery App (2019-2020)
        - **Infrastructure Engineer** at Meitu Inc. (2016-2018)
        - **Backend Developer** at Xunlei Limited (2014-2015)

  - block: markdown  
    content:
      title: "Technical Skills"
      text: |
        ### Programming Languages
        - **Go** (9+ years) - Expert level, microservices architecture
        - **Python** (4+ years) - AI/ML integration, automation
        - **C/SQL** - Proficient in systems programming and database design
        
        ### Infrastructure & DevOps
        - **Kubernetes** - Container orchestration, custom CRDs, GPU scheduling
        - **Docker, GitLab CI, ArgoCD, Harbor** - Complete CI/CD pipeline
        - **Microservices** - Gin, Beego, gRPC, Protobuf architecture
        
        ### Data & Messaging
        - **Databases** - PostgreSQL, MySQL, MongoDB, Redis, ClickHouse
        - **Message Queues** - Kafka, RabbitMQ, APISIX gateway
        - **Monitoring** - Prometheus, comprehensive logging systems

  - block: markdown
    content:
      title: "Education & Open Source"
      text: |
        ## Education
        
        **Beijing Jiaotong University** — Master of Software Engineering (2011-2014)
        - Internships: Tencent (Nov 2011 – Aug 2012), Baidu (Apr 2013 – Sep 2013)
        
        **Beihang University** — Bachelor of Software Engineering (2007-2011)
        - Awards: Second-Class Scholarship; 2nd Prize, Microsoft Imagination Cup
        
        ## Open Source Contributions
        
        **chDB (Python Library)** - Active contributor to chDB-io project enabling SQL-like queries on flat files
        
        **CovenantSQL** - Major contributor to open-source blockchain database (1.5k+ GitHub stars)
        
        **GNTE** - Created network simulation tool that reached GitHub Trending

  - block: markdown
    content:
      title: "Contact Information"
      text: |
        ## Get In Touch
        
        Feel free to reach out for collaboration opportunities or technical discussions.
        
        📧 **Email:** [job@laodouya.com](mailto:job@laodouya.com)  
        📱 **Phone:** [+86 15810540933](tel:+8615810540933)  
        🔗 **GitHub:** [github.com/laodouya](https://github.com/laodouya)  
        📍 **Location:** Shenzhen, Guangdong, China
---