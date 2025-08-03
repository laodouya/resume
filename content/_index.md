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
      title: Xu Jin
      text: |-
        **Senior Software Architect & Platform Lead**
        
        11+ years experience in Go, Python, and distributed systems architecture.  
        Specialized in AI platforms, microservices, and enterprise solutions.
        
        📍 Shenzhen, China | 💼 11 Years Experience | 🛠️ Go (9 years), Python (4 years)
      primary_action:
        text: Download Resume
        url: uploads/xujin-resume.pdf
      secondary_action:
        text: Contact Me  
        url: 'mailto:job@laodouya.com'
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: markdown
    id: about
    content:
      title: About Me
      text: |
        ## Senior Software Architect & Platform Lead
        
        I am a seasoned software architect with **11+ years of experience** specializing in:
        
        - 🏗️ **Distributed Systems Architecture** - Microservices, API design, scalable platforms
        - 🤖 **AI/ML Platform Development** - Training pipelines, model deployment, GPU optimization  
        - ☁️ **Cloud Native Technologies** - Kubernetes, Docker, CI/CD, DevOps practices
        - 💼 **Enterprise Solutions** - Multi-tenant SaaS, licensing systems, client integrations
        - 🌟 **Open Source Leadership** - Major contributor to blockchain databases and developer tools
        
        Currently leading platform architecture at **GDDI Innovation Technology**, focusing on AI training infrastructure and enterprise deployment solutions for 20+ customers.
        
        **Core Technologies:** Go (9+ years), Python (4+ years), Kubernetes, PostgreSQL, Redis, Kafka
  - block: features
    content:
      title: Skills
      items:
        - name: Go Programming
          description: 9+ years of experience in Go development, microservices architecture, and distributed systems
          icon: code-bracket
          icon_pack: hero
        - name: Python & AI/ML
          description: 4+ years in Python development, AI model integration, and machine learning platforms
          icon: cpu-chip
          icon_pack: hero
        - name: Kubernetes & DevOps
          description: Expert in container orchestration, CI/CD pipelines, and cloud-native infrastructure
          icon: server
          icon_pack: hero
        - name: Database Systems
          description: Proficient in PostgreSQL, MySQL, MongoDB, Redis, and ClickHouse
          icon: circle-stack
          icon_pack: hero
        - name: Microservices
          description: Extensive experience with gRPC, Protobuf, message queues, and API gateways
          icon: puzzle-piece
          icon_pack: hero
        - name: Open Source
          description: Active contributor to blockchain databases and network simulation tools
          icon: heart
          icon_pack: hero
  - block: markdown
    content:
      title: Professional Experience
      text: |
        ## Current Position
        
        ### 🏢 GDDI Innovation Technology Co., Ltd. — Shenzhen
        **Head of Software Platform, Architect** | *Oct 2023 – Present*
        
        - 🚀 **AI Training & Annotation Platform**: Architected complete redesign of dual AI platforms using microservices with Go, Kubernetes, and custom CRDs
        - ⚙️ **GPU Optimization**: Built custom Kubernetes scheduling middleware with nvidia-k8s-plugin for optimal GPU workload allocation
        - 🏢 **Enterprise Deployment**: Successfully deployed to 20+ enterprise customers with complex multi-GPU configurations
        - 🔄 **DevOps Pipeline**: Established comprehensive CI testing framework and ArgoCD-based deployment system
        
        ---
        
        ## Previous Experience
        
        ### 🌐 Xunlei Limited — Shenzhen  
        **System Architect, InfoSec Department** | *Apr 2020 – Jun 2023*
        
        - 💰 **SaaS Platform**: Architected enterprise platform serving 20+ clients with ~¥500K monthly revenue
        - 📈 **Performance**: Improved reviewer accuracy from 88% to 98%, reduced wait time from 15min to 2min  
        - 🔐 **SDK Development**: Created multilingual SDKs with RSA encryption for 20+ enterprise integrations
        - 🤖 **AI Optimization**: Built model service pipeline reducing GPU pressure by 80%
        
        ### ⛓️ CovenantSQL — Remote
        **Core Developer** | *May 2018 – Nov 2019*
        
        - 🌟 **Blockchain Database**: Core contributor to decentralized SQL database (1.5k+ GitHub stars)
        - 🔧 **GNTE Tool**: Built network simulation tool that reached GitHub Trending
        - 📚 **SDK Ecosystem**: Developed CLI tools, Python/Java drivers and client libraries
        
        ### 🛒 Shanxian Daojia Grocery App
        **Tech Manager** | *Nov 2019 – Apr 2020*
        
        - 🏗️ **Infrastructure**: Built complete backend from scratch, leading 6-member team
        - 💳 **Payment Integration**: Implemented WeChat/Alipay and rider dispatch algorithms
        
        ### 📱 Meitu Inc. — Shenzhen
        **Infrastructure Engineer** | *Jan 2016 – Apr 2018*
        
        - 📦 **Core Libraries**: Developed Go libraries for Etcd, logging, and storage
        - 📺 **Live Streaming**: Built RTMP transcoding services with FFmpeg optimization
        
        ### ⚡ Xunlei Limited  
        **Backend Developer** | *Jul 2014 – Oct 2015*
        
        - 🔍 **P2P Systems**: Developed BT-Box torrent indexing for content discovery
        - 🌐 **CDN**: Built distributed CDN client based on Nginx architecture
    design:
      columns: '1'
  - block: markdown
    content:
      title: Education & Open Source
      text: |
        ## 🎓 Education
        
        ### Beijing Jiaotong University
        **Master of Software Engineering** | *2011 - 2014*
        - 💼 Internships: Tencent (2011-2012), Baidu (2013)
        
        ### Beihang University  
        **Bachelor of Software Engineering** | *2007 - 2011*
        - 🏆 Awards: Second-Class Scholarship, Microsoft Imagination Cup 2nd Prize
        
        ---
        
        ## 🌟 Open Source Contributions
        
        ### [chDB Python Library](https://github.com/chdb-io/chdb)
        Active contributor enabling SQL queries on flat files (CSV, Parquet) using ClickHouse engine
        
        ### [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) 
        Major contributor to blockchain database project (1.5k+ stars) with comprehensive SDK ecosystem
        
        ### GNTE Network Emulator
        Creator of network simulation tool for distributed system testing (GitHub Trending)
    design:
      columns: '1'
  - block: markdown
    content:
      title: Contact Me
      text: |
        ## 📬 Get In Touch
        
        Feel free to reach out for collaboration opportunities or technical discussions!
        
        📧 **Email:** [job@laodouya.com](mailto:job@laodouya.com)  
        📱 **Phone:** [+86 15810540933](tel:+8615810540933)  
        🔗 **GitHub:** [github.com/laodouya](https://github.com/laodouya)  
        📍 **Location:** Shenzhen, Guangdong, China  
        📄 **Resume:** [Download PDF](uploads/xujin-resume.pdf)
    design:
      columns: '1'
---