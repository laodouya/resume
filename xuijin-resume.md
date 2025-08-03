# Xu Jin

- **Location:** Shenzhen, China
- **Experience:** 11 Years | **Languages:** Go (9 years), Python (4 years)
- **Phone:** +86 15810540933
- **Email:** job@laodouya.com
- **GitHub:** [github.com/laodouya](https://github.com/laodouya)

---

## Education

**Beijing Jiaotong University** — Master of Software Engineering
*Sep 2011 – Jul 2014*
- Internships: Tencent (Nov 2011 – Aug 2012), Baidu (Apr 2013 – Sep 2013)

**Beihang University** — Bachelor of Software Engineering
*Sep 2007 – Jul 2011*
- Awards: Second-Class Scholarship; 2nd Prize, Microsoft Imagination Cup; SRTP (Student Research Training Program);

---

## Work Experience

### GDDI Innovation Technology Co., Ltd. — Shenzhen
**Head of Software Platform, Architect**
*Oct 2023 – Present*

**AI Training & Annotation Platform Architecture**
- Architected and led complete redesign of dual AI platforms (training + annotation) using microservices architecture with Go (Gin/Beego/Gorm), Protobuf, and Kubernetes deployment
- Developed dataset management, training task scheduling, training container management, model orchestration, and inference platform device management modules
- Built custom Kubernetes scheduling middleware and customized nvidia-k8s-plugin with GPU SN identification capabilities to optimize GPU workload allocation
- Developed custom resource definitions (CRDs) to manage multi-pod task relationships and maintain training task continuity on same nodes, reducing data replication overhead
- Integrated multiple SOTA AI models (Sam2, Florence2, YoloE, GroundingDino) for automated annotation capabilities with performance-based product interaction design
- Established Self-Host Harbor + GitLab CI pipeline for automated image builds and k8s API integration for platform configuration updates

**Enterprise Deployment & Licensing (20+ customers self-hosted deployed)**
- Designed comprehensive offline licensing system supporting year/device/model/video-stream authorization modes with encryption-based license control
- Successfully deployed to 20+ enterprise customers, including complex configurations: single-machine 8-GPU and 8-machine training clusters
- Integrated custom SSO solutions and provided hardware consultation, resolving multiple customer infrastructure issues

**Engineering Leadership & Quality Management**
- Built comprehensive CI testing framework including integration, regression, API, and UI testing for quality assurance
- Implemented ArgoCD-based deployment system with automated k8s rollouts, version management, and service rollback capabilities
- Optimized datacenter network layout and managed training servers, database servers, code repositories, and Docker image registries
- Led cross-functional team (backend/frontend/QA/DevOps) and managed product-algorithm collaboration via Jira project management

### Xunlei Limited — Shenzhen
**System Architect, InfoSec Department**
*Apr 2020 – Jun 2023*

**Commercial SaaS Platform & Content Censorship System (Built from scratch)**
- Architected and developed enterprise SaaS platform serving 20+ clients with ~¥500K monthly revenue
- Designed multi-tenant architecture with RBAC permissions, financial billing modules, automated account management, and customer relationship management
- Built microservices using Go-Gin framework, PostgreSQL with GORM, Redis, Kafka, RabbitMQ, Etcd, integrated with APISIX gateway
- Implemented APISIX gateway plugins for seamless authentication forwarding and service routing
- Separated services by business characteristics: platform service, auth/account service, automated censorship service, manual censorship service, and statistical reporting service

**Performance & Quality Improvements**
- Improved reviewer accuracy from 88% to 98% and reduced average wait time from 15 minutes to 2 minutes
- Redesigned task assignment workflow, eliminating business-specific review queues for streamlined dispatch system
- Implemented blind review, quality inspection, and performance-based compensation systems with state machine control
- Added comprehensive Prometheus monitoring for response times and call frequencies to proactively identify bottlenecks
- Optimized database performance by separating hot/cold data and isolating low-frequency global searches from high-frequency operations

**Advanced Security & Architecture**
- Implemented Bcrypt password encryption with Base64+RSA front-end communication to prevent man-in-the-middle attacks
- Designed Snowflake ID-based distributed unique ID generation across multiple service nodes
- Built comprehensive financial system with transaction logs + balance tables to ensure accurate accounting, using integer storage for all amounts
- Implemented token bucket algorithm for QPS rate limiting per customer

**SDK Development & Client Integration**
- Developed multilingual SDKs with RSA key + API-Key encryption for 20+ enterprise clients
- Created comprehensive API documentation and provided technical integration support for client onboarding
- Successfully deployed SDKs and conducted integration testing for 10+ production clients
- Designed RSA encryption keys and API-Key systems for secure interface data transmission

**AI Model Service Development & Optimization**
- Developed Python Worker services for multiple scenario-based BERT models delivered by algorithm team
- Built preprocessing optimization workflows for screenshot elongated images and image rotation evasion detection
- Designed hierarchical strategy threshold priority structure with four-layer configuration: deployment environment, enterprise, application, and module levels
- Implemented context-aware violation detection with atmosphere patrol system for enhanced relational data identification (patent pre-authorized)

**Performance Optimization & Cost Reduction**
- Developed blacklist/whitelist filtering services (video, image, text) reducing GPU model service pressure by 80% deduplication rate in group chat images
- Successfully merged 5 individual models into 1 unified pipeline, significantly reducing infrastructure costs
- Built comprehensive model scheduling engine in Python to coordinate multiple Worker services with priority-based strategy matching

### Shanxian Daojia Grocery App
**Tech Manager**
*Nov 2019 – Apr 2020*
- Built complete backend infrastructure from scratch using Go, leading a 6-member team (4 backend, 2 mobile developers)
- Architected and implemented core features: SKU management system, WeChat/Alipay payment integration, rider dispatch and scheduling algorithms, billing system, and promotional coupon engine
- Managed technical project planning, task breakdown, progress tracking, and cross-team coordination for grocery delivery platform
- Designed scalable microservices architecture supporting real-time order processing and delivery logistics

### CovenantSQL (Open Source Blockchain Database)
**Core Developer**
*May 2018 – Nov 2019*
- Core contributor to decentralized SQL database with blockchain characteristics (1.5k+ GitHub stars)
- Architected two-layer structure with main chain for transaction settlement and sub-chains for data storage, ensuring data immutability and traceability while maintaining usable storage performance
- Developed comprehensive SDK ecosystem: CQL command-line tool, Python-driver, Java-driver, and client libraries
- Built GNTE (Global Network Topology Emulator, GitHub Trending featured) network latency simulation tool for distributed system testing
- Conducted distributed linear consistency testing and performance benchmarking for blockchain database systems

### Meitu Inc. — Shenzhen
**Infrastructure Engineer, Architecture Platform**
*Jan 2016 – Apr 2018*

**Infrastructure & Toolchain Development**
- Developed core Go libraries including Etcd wrapper for simplified operations and standardized storage formats, and comprehensive logging library
- Spearheaded adoption of modern development practices: Git branch management models, Go dependency management tools, and continuous integration processes
- Conducted technology research on emerging trends including blockchain technology, Bitcoin, and EOS projects

**Business Support Services**
- Developed and maintained RTMP transcoding services using FFmpeg source code analysis and parameter optimization for live streaming infrastructure
- Built backend services for social IM products including TCP long-connection services, message processing systems, and operational activity platforms
- Provided architectural support and consulting for various product teams across the organization

### Xunlei Limited — Membership & CDN Branch
**Backend Developer**
*Jul 2014 – Oct 2015*
- Developed high-performance BT-Box torrent indexing service for P2P content discovery and management
- Built distributed CDN client application based on Nginx architecture for content delivery network optimization
- Implemented backend services supporting membership management and content distribution systems

---

## Technical Skills

- **Programming Languages:** Go (9+ years), Python (4+ years), C, SQL
- **Backend Frameworks:** Gin, Gorm, Beego, FastAPI, Tornado
- **Infrastructure & DevOps:** Kubernetes, Docker, GitLab CI, ArgoCD, Harbor
- **Databases & Storage:** MySQL, PostgreSQL, MongoDB, Redis, Etcd, ClickHouse
- **Message & Networking:** Kafka, RabbitMQ, APISIX, gRPC, ProtoBuf, RTMP, TCP/IP, HTTP
- **Monitoring & Security:** Prometheus, RSA/Bcrypt encryption, RBAC, Multi-tenant architecture
- **Development Practices:** Microservices, CI/CD, Agile/Scrum, Code Review, Git workflows
- **AI/ML Integration:** ONNX model deployment, GPU optimization, SOTA model integration (Sam2, Florence2, YoloE)

---

## Open Source Contributions

**chDB (Python Library) - Active Contributor**
- Early contributor to the chDB-io project, enabling SQL-like queries on flat files (CSV, Parquet, etc.) directly in Python
- Based on the ClickHouse engine, supporting high-performance analytics without the need for full database setup

**CovenantSQL - Core Developer**
- Major contributor to open-source blockchain database project (1.5k+ GitHub stars)
- Developed multiple SDK implementations and tooling ecosystem
- Created GNTE (Global Network Topology Emulator) network simulation tool that reached GitHub Trending

---

