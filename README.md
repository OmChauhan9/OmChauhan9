# Om Chauhan

M.S. Software Engineering student at Arizona State University focused on **backend systems, cloud infrastructure, systems programming, and AI tooling**.

I build production-style systems using **Java, C++, Spring Boot, Node.js, PostgreSQL, AWS, GCP, Docker, Terraform, LangGraph, and GitHub Actions**.

Currently seeking **2026 Software Engineering / Backend / Cloud / Platform / Systems / AI Tooling roles**.

<p align="center">
  <a href="https://www.linkedin.com/in/omchauhan9203/">
    <img src="https://img.shields.io/badge/LinkedIn-Om%20Chauhan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:omrajesh9203@gmail.com">
    <img src="https://img.shields.io/badge/Email-omrajesh9203%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://omchauhan9.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-Website-4B8BBE?style=for-the-badge" />
  </a>
  <a href="https://github.com/OmChauhan9/OmChauhan9/raw/main/Om_Chauhan_Resume.pdf">
    <img src="https://img.shields.io/badge/Resume-PDF-43A047?style=for-the-badge" />
  </a>
</p>

---

## Featured Systems & AI Projects

### C++ Limit Order Book & Matching Engine

C++20 exchange-style matching engine supporting limit/market orders, cancel/modify requests, partial fills, best bid/ask queries, and strict price-time priority.

- Built deterministic replay and 80+ GoogleTest cases
- Processed 1.2M synthetic order events/sec with sub-15us p99 latency
- Improved cancel/modify lookup to O(1) average time using direct order-ID indexing

**Tech:** C++20 · GoogleTest · Order Book · Low-Latency Systems · Data Structures  
**Status:** Repo/case study not public yet

---

### C++ Market Data Parser & Event Pipeline

Byte-level C++ market data parser that normalizes simulated exchange messages into internal order events while handling malformed lines, missing fields, invalid numeric values, and duplicate order IDs safely.

- Parsed 6M+ records/sec using direct byte scanning and primitive conversion
- Increased event-pipeline throughput from 3.8M to 24.0M messages/sec using an SPSC ring buffer
- Replaced a mutex-protected queue with cache-line-separated atomic producer/consumer indices

**Tech:** C++ · Byte Parsing · SPSC Ring Buffer · Atomics · Event Pipeline  
**Status:** Repo/case study not public yet

---

### Agentic Finance Research System

LangGraph-based multi-agent workflow using a supervisor-controller pattern to decompose finance queries across news retrieval, financial statement analysis, SQL screening, analyst outlook, and sector research.

- Combined yfinance market data, DuckDB filters, and web-search grounding
- Generated source-backed investment research reports with confidence scoring
- Produced structured Markdown output for repeatable research workflows

**Tech:** Python · LangGraph · LangChain · DuckDB · yfinance · Agentic AI  
**Status:** Repo/case study not public yet

---

### CiteLens — Mini Deep Research Agent

LangGraph-based research agent that decomposes user questions, retrieves supporting evidence from indexed documents, and generates citation-grounded answers using a RAG pipeline with FAISS.

- Implemented a citation verifier node with LangSmith tracing and evaluation
- Flags unsupported claims by comparing generated answers against retrieved context
- Improves hallucination detection across benchmark queries

**Tech:** Python · LangGraph · RAG · FAISS · LangSmith · Evaluation  
**Status:** Repo/case study not public yet

---

## Featured Backend & Cloud Projects

### [StratusVault — Secure Cloud File Share](https://github.com/OmChauhan9/stratusvault-secure-cloud-file-share)

Secure cloud-native document locker built with **Spring Boot, Firebase Auth, PostgreSQL, Google Cloud Storage, and Cloud Run**.

- Implemented server-side Firebase ID token verification
- Designed file-level access control with owner-managed read-only sharing
- Stored file metadata and permissions in PostgreSQL
- Kept object storage private with no public bucket exposure

**Tech:** Java · Spring Boot · Firebase Auth · PostgreSQL · GCP Cloud Run · Cloud Storage

---

### [Hybrid Cloud & Edge AI System](https://github.com/OmChauhan9/hybrid-cloud-edge-ai-system)

AWS edge/cloud inference pipeline using **IoT Greengrass, SQS, Lambda, EC2, Docker, and PyTorch**.

- Built a queue-depth autoscaling controller for up to 15 EC2 app-tier instances
- Ran face detection at the edge using MTCNN
- Sent detected face crops to the cloud instead of raw frames
- Achieved sub-1.2s average latency across benchmark requests

**Tech:** Python · PyTorch · AWS EC2 · Lambda · SQS · S3 · IoT Greengrass · Docker · MQTT

---

### [AWS CI/CD Java Deployment Pipeline](https://github.com/OmChauhan9/aws-cicd-java-deployment-pipeline)

Automated deployment pipeline for a Maven Java web app packaged as a WAR and deployed to EC2 Tomcat.

- Used CodePipeline, CodeBuild, CodeDeploy, CodeArtifact, and S3 artifacts
- Automated build, test, package, and deployment stages
- Used Bash lifecycle hooks for Tomcat deployment on EC2

**Tech:** AWS · CodePipeline · CodeBuild · CodeDeploy · CodeArtifact · EC2 · Maven · Tomcat

---

### [Realtime Socket.IO Chat System](https://github.com/OmChauhan9/realtime-socketio-chat-system)

Real-time chat backend built with **Node.js, Express, Socket.IO, SQLite, and Node.js Cluster**.

- Added persistent message storage
- Implemented client-side retries and duplicate-message prevention
- Demonstrated connection state recovery and multi-worker Socket.IO coordination

**Tech:** Node.js · Express · Socket.IO · SQLite · WebSockets · Cluster

---

### [NOAH Programming Language Interpreter](https://github.com/OmChauhan9/noah-programming-language)

Custom statically typed programming language implemented in **Java using ANTLR4**.

- Built grammar, lexer/parser flow, parse-tree traversal, and runtime evaluation
- Supports typed variables, expressions, conditionals, loops, and runtime error handling

**Tech:** Java · ANTLR4 · Interpreter · Parser · Language Design · Maven

---

## Core Stack

**Languages:** Java · Python · C++ · C · C# · SQL · PL/SQL · JavaScript/TypeScript  
**Backend:** Spring Boot · Spring MVC · Spring Security · Spring Cloud · Hibernate · Node.js · Express · Flask · REST APIs · GraphQL · Socket.IO · JUnit  
**Cloud & Databases:** AWS · GCP · Azure · Firebase · PostgreSQL · MySQL · MongoDB · Redis · SQLite · DynamoDB · SQL Server · Oracle  
**DevOps & Tools:** Docker · Kubernetes · Terraform · CI/CD · Git · GitHub Actions · Jenkins · CircleCI · Linux · Postman · Swagger · Insomnia  
**AI/ML & Agents:** PyTorch · TensorFlow · Hugging Face · Pandas · NumPy · LangChain · LangGraph · LangSmith · RAG · FAISS · YOLOv5 · OpenCV  
**Frontend:** React · React Native · Next.js · Angular · Redux · React Query · Bootstrap · Tailwind CSS

---

## Experience

**Software Engineer Intern — Axisray**  
Ahmedabad, India · Jun 2023 – Jun 2024

- Built a full-stack HR automation system using Spring Boot and MySQL for a 50+ person team
- Integrated Amazon Alexa Skills Kit with AWS Lambda for voice-driven HR queries
- Automated deployment workflows using AWS CodePipeline, CodeBuild, CodeDeploy, CodeArtifact, and GitHub webhooks
- Developed a YOLOv5-based fire detection system using a custom dataset of 10,000 images and 100 videos

---

## Education

**Arizona State University**  
M.S. Software Engineering · Expected May 2026 · GPA: 3.78/4.0

**Gujarat Technological University**  
B.E. Computer Engineering · May 2024 · GPA: 3.39/4.0

---

## Links

- Portfolio: https://omchauhan9.github.io/
- LinkedIn: https://www.linkedin.com/in/omchauhan9203/
- GitHub: https://github.com/OmChauhan9
- Medium: https://medium.com/@omrajesh9203
- Resume: https://github.com/OmChauhan9/OmChauhan9/raw/main/Om_Chauhan_Resume.pdf
- Email: omrajesh9203@gmail.com
