# RAMIRO YAIR ROMÁN TREJO
**Software Engineer | Junior Backend & DevOps Engineer**  
Zacatecas, Mexico • (+52) 492-181-9531 • [ryrt32@gmail.com](mailto:ryrt32@gmail.com)  
**Portfolio:** [roman-mx.tech](https://roman-mx.tech) • **GitHub:** [github.com/YairRT45](https://github.com/YairRT45) • **GitLab:** [gitlab.com/ryrt32](https://gitlab.com/ryrt32) • **LinkedIn:** [linkedin.com/in/ramiro-yair-román-trejo-1bb164383](https://www.linkedin.com/in/ramiro-yair-román-trejo-1bb164383/)

---

### PROFESSIONAL SUMMARY

Software Engineer with rigorous **Computer Science foundations (low-level data structures, graph theory, compiler parsers, and cryptography)**, specialized in **Backend Architecture (Python, Django, FastAPI)**, **DevOps infrastructure (Docker Compose, Jenkins, AWS EC2, Nginx)**, production observability (**Prometheus, Grafana**), and **Computer Vision / AI pipelines (YOLOv8, PyTorch)**. Proven experience delivering production web platforms in industrial manufacturing environments (Compañía Cervecera de Zacatecas / Grupo Modelo - AB InBev), academic institutional systems, and leading software verification and validation (IV&V) teams. Disciplined engineering mindset rooted in quality frameworks (Humphrey's Personal Software Process - PSP / SEI), automated BDD/E2E testing (Behave, Selenium), and zero-friction CI/CD delivery.

---

### TECHNICAL SKILLS

* **Languages:** Python 3.x, Java, Kotlin, Dart, SQL, C#, JavaScript, PHP, C/C++.
* **Backend & APIs:** Django 5.x, Django REST Framework (DRF), FastAPI (Async/Microservices), Spring Boot, Laravel 8, MVC/RESTful Architecture, Apache (mod_wsgi), TCP/IP Sockets.
* **DevOps & Cloud:** Docker, Docker Compose (Polyglot Multi-Container Stacks & Isolated Networks), Linux (Ubuntu Server, Debian, Bash Scripting), Jenkins (Declarative `Jenkinsfile` Pipelines), GitHub Actions (CI/CD), AWS EC2, Nginx Proxy Manager, SSL/TLS (Let's Encrypt), SSH Automation.
* **Observability & SRE:** Prometheus, Grafana (Real-Time Dashboards), Alertmanager, Node Exporter, cAdvisor, Blackbox Exporter, MariaDB Exporter, PromQL Alerting Rules.
* **Computer Science (CS) Foundations:** Memory-level linear & non-linear data structures in pure Java (Binary Search Trees - BST, Min/Max Heaps, Arithmetic Expression Trees, Priority Queues), Graph Theory & **Dijkstra's Shortest Path Algorithm**, Stack-based Compilers & Syntax Parsers, Raw WAV Audio Signal Processing, 2D/3D Matrix Tensors for Digital Image Transformations, Hidden Markov Models (HMM).
* **Artificial Intelligence & Computer Vision:** Supervised training of **Ultralytics YOLO (v5/v8)** models with **PyTorch** for agricultural foliage disease classification, dataset curation and augmentation with AgML, visual attention heatmaps (`ver_atencion_yolo.py`), optimized model weight exporting for edge mobile inference.
* **Cryptography & Applied Security:** Asymmetric RSA Cryptosystem (Client-Server Architecture over TCP Sockets in Python), RC4 Stream Cipher, Alberti Cipher Disc, Cryptanalysis, Shannon Entropy, Hamming Weight, Sieve of Eratosthenes for prime generation.
* **Databases (SQL & NoSQL):** PostgreSQL 15/16, MariaDB, MySQL 8.0, MongoDB 6 (NoSQL Document Store), SQLite, Room Database (Android ORM), Oracle PL/SQL (Procedures & Triggers).
* **Quality Assurance, Testing & Methodologies:** Humphrey's Personal Software Process (PSP / SEI) with LOC/NPM tracking and statistical regression estimation; Independent Verification and Validation (IV&V), BDD Testing (Behave, Gherkin), Selenium WebDriver (Firefox Headless in CI), Flake8 Linters, Unit Testing (pytest, unittest), Root Cause Analysis (RCA), Agile / Scrum.
* **Mobile & Cross-Platform Development:** Flutter & Dart (SQLite FFI, BLoC Pattern), Native Android with Kotlin (Android Jetpack, MVVM, Room DB, Google Maps API).

---

### WORK EXPERIENCE & TECHNICAL LEADERSHIP

#### Web Developer / Software Consultant
**Compañía Cervecera de Zacatecas (Grupo Modelo / AB InBev)** | *Aug 2026 – Oct 2026*
* Architected and developed a centralized web platform for real-time tracking, auditing, and traceability of Good Operating Practices (GOPs) and tooling across the Packaging Department.
* Significantly reduced manual logging overhead by digitizing inspection workflows, evidence capturing, and automated action plan generation on the manufacturing plant floor.
* Structured relational data models and operational interfaces in **Django 5.0** and **PostgreSQL 16**, deploying a multi-container stack with **Docker Compose** and persistent volumes.
* Analyzed plant floor operational metrics (**MTTR** - Mean Time To Repair and **LEF** - Line Efficiency), integrating automated pipelines between SharePoint, corporate Excel sheets, and Power BI analytical models.

#### Technical Lead & Backend Developer
**Universidad Autónoma de Zacatecas (UAZ) – Licenciatura en Lenguas Extranjeras** | *Nov 2025 – May 2026*
* Led end-to-end development of the university academic management platform with **Python, Django, and MariaDB**, containerized over Debian with Apache `mod_wsgi`.
* Built an automated CI/CD pipeline in **Jenkins (`Jenkinsfile`)** featuring **Flake8** linting, unit test suites, semantic versioning, and secure pushes to a private Docker registry (`registry.roman-mx.tech`).
* Implemented **BDD acceptance testing with Behave** orchestrated over an isolated network with **Selenium WebDriver (Firefox Headless)** to validate critical user journeys prior to deployment.
* Automated continuous deployment via **SSH into remote AWS EC2 production servers**, establishing dynamic version rollbacks (`IMAGE_VERSION_OLD`) via environment variables for zero-downtime releases.

#### Quality Assurance Lead (QA Lead) & Android Developer
**MovilSecure (4Nodos Collaborative Project)** | *Oct 2025 – Nov 2025*
* Designed and executed formal **Independent Verification and Validation (IV&V)** procedures, engineering audits of functional specifications, and requirements traceability matrices.
* Conducted formal Design Reviews and cross-team Code Reviews, enforcing strict acceptance criteria for Pull Request approvals.
* Contributed to native **Kotlin** development under **MVVM architecture**, structuring local offline caching with **Room Database (SQLite)** and integrating **Google Maps API** for medical emergency routing and caregiver safe zones.

#### Quality Assurance Inspector (QA)
**Nagakura Engineering Works** | *Apr 2021 – Jul 2022*
* Executed and supervised precision dimensional and material inspection protocols under tight manufacturing industrial tolerances.
* Detected, isolated, and documented non-conformances across production lines; applied **Root Cause Analysis (RCA)** to establish immediate corrective action plans.
* Audited raw material technical specifications and ensured ISO manufacturing quality standards compliance.

---

### FEATURED TECHNICAL PROJECTS

* **Doctor Chile – AI Crop Pathology Detection System (YOLO) & Mobile App (`doctor_chile_app` & `yolo_chili_training`):**  
  End-to-end Computer Vision and mobile solution for plant pathology diagnosis in chili crops. Supervised training of **Ultralytics YOLO (v5/v8)** models using **PyTorch** classifying 5 foliar conditions (`Curl`, `Healthy`, `Spot`, `Whitefly`, `Yellowish`), coupled with AgML dataset curation, visual attention heatmaps, and edge inference optimization. Built cross-platform mobile client in **Flutter & Dart** with offline-first SQLite FFI persistence and automated CI/CD quality gates in **GitHub Actions** (`flutter analyze --fatal-infos` and unit testing).

* **Core Data Structures, Dijkstra's Algorithm & Syntax Compiler in Java (`data-structures-and-algorithms-java`):**  
  Built from scratch at the memory level (zero dependency on `java.util` collections): Binary Search Trees (BST), Heaps/Priority Queues, Arithmetic Expression Trees with Infix/Postfix conversion, and directed graphs featuring shortest-path optimization via **Dijkstra's Algorithm** and DFS/BFS traversals. Includes a stack-based syntax compiler/parser, low-level RIFF/PCM binary WAV audio processing, and 2D/3D matrix algebra for digital image transformations.

* **Polyglot Microservices Mesh with Docker Compose (`examen1-deploy`):**  
  Multi-container orchestration coordinating 4 heterogeneous technologies in an isolated mesh: **FastAPI (Python) + PostgreSQL 15**, **Spring Boot (Java) + MongoDB 6 (NoSQL)**, **Laravel 8 (PHP) + MySQL 8.0**, and **React Admin** (consuming the FastAPI layer). Engineered network segmentation (`frontend` public / `backend` private), active health checks (`pg_isready`, `mongosh ping`) for orderly boot sequencing, and SSL reverse proxy routing with Nginx Proxy Manager.

* **Cloud Observability & Telemetry Stack on AWS (`Observabilidad`):**  
  Full-stack monitoring infrastructure deployment with **Prometheus, Grafana, and Alertmanager**. Low-level system telemetry ingestion via **Node Exporter** (Linux host) and **cAdvisor** (Docker containers), Django and MariaDB service metrics collection, synthetic HTTP latency probes with **Blackbox Exporter**, and automated PromQL alerting rules.

* **UPN-SASCE University Enrollment Platform (`UPN-SASCE`):**  
  Enterprise student scheduling and academic enrollment system for **Universidad Pedagógica Nacional (UPN)**. Architecture built on **Django** and **PostgreSQL**, containerized with **Docker Compose**, integrated with a **Jenkins** CI/CD pipeline, and backed by automated BDD tests in **Behave** covering complex scheduling and prerequisite rules.

---

### EDUCATION

* **B.S. in Software Engineering** — Universidad Autónoma de Zacatecas (UAZ) *(In progress, Expected Graduation: 2026)*

---

### LANGUAGES

* **Spanish:** Native
* **English:** Intermediate Technical (B1/B2) — Fluent reading and writing of architecture RFCs, technical documentation, code reviews, and commit messages; professional conversational competence.
