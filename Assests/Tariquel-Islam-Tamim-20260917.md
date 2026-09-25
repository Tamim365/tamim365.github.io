# Md. Tariquel Islam Tamim
**Senior Backend, Cloud & AI Engineer**

📍 Dhaka, Bangladesh | 📞 +8801710525540 | ✉️ tamim.365.ti@gmail.com
🔗 **GitHub:** [tamim365](https://github.com/tamim365) | 🔗 **LinkedIn:** [Tamim365](https://linkedin.com/in/Tamim365)

---

## 🎯 Professional Summary
Backend and cloud engineer with ~5 years of experience building and operating production systems for international (notably Japanese) clients. The last 3 years have been heavily focused on owning backends end-to-end: architecture, API design, async processing, AWS infrastructure, and CI/CD pipelines. 

I am the primary author of four production backends (Laravel and Django) and the Infrastructure as Code (IaC) that deploys them. My recent work centers on advanced LLM/agent systems—including multi-agent orchestration, RAG over vector databases, and computer-vision inference services—alongside large-scale video streaming and payment integrations.

---

## 🛠️ Technical Stack
*   **Languages:** PHP (Laravel 9–12), Python 3.12+ (Django/DRF, FastAPI), JavaScript/TypeScript, SQL, C/C++, Java, Dart (Flutter)
*   **Cloud Infrastructure (AWS):** EC2, ECS, ECR, Lambda, S3, RDS (MySQL/Aurora/PostgreSQL), ElastiCache/Redis, SQS, SNS, MediaConvert, CloudFront, ALB, Auto Scaling, VPC, IAM, Secrets Manager, SSM Parameter Store, CloudWatch, CodePipeline, CodeBuild, CodeDeploy, DynamoDB
*   **IaC & DevOps:** AWS CDK (TypeScript), Terraform, Docker & Docker Compose, Nginx, Supervisor, GitHub Actions, Linux
*   **Databases & Search:** MySQL, PostgreSQL, Redis, Elasticsearch, Weaviate (vector database), OpenSearch/Kibana
*   **AI / ML:** OpenAI, Anthropic, LangChain, LangGraph, Agno, LiteLLM, MCP, Dify (self-hosted), RAG & vector search, prompt engineering, PyTorch / Vision Transformer inference, Speech-to-Text (Amazon Transcribe, Google Cloud Speech, ElevenLabs)
*   **Async & Messaging:** Celery (SQS/Redis brokers), Laravel Queues on SQS, Procrastinate, cron/scheduler design, WebSockets (Django Channels, Pusher)
*   **Integrations:** Stripe, Firebase/FCM & Firestore, LINE Messaging API & LINE Login (OIDC), Google Business Profile, Instagram Graph API, Facebook Graph, Google Ads, GA4, SendGrid, Adjust, Rakuten SMS

---

## 💼 Professional Experience

### **JB Connect Ltd.** | *Senior Software Engineer - Team Lead*
*Apr 2023 – Present*

*   **Architecture & Team Leadership:** Promoted to lead system architecture and engineering, serving as the primary author across core production backends (~88% commit contribution on a 2,100-commit Laravel codebase). Led code reviews, mentored engineers, and authored architecture decision records (ADRs) to maintain technical standards.
*   **Cloud Infrastructure:** Provisioned production AWS environments (VPCs, ECS, Aurora) and automated CI/CD pipelines using AWS CDK (TypeScript) and Terraform, ensuring zero-downtime deployments and preventing configuration drift.
*   **AI & Enterprise Systems:** Architected AI/ML microservices including multi-agent orchestrations (LangGraph/Agno), Weaviate-grounded RAG pipelines, and PyTorch Vision-Transformer image defect detection.
*   **Async & Media Workflows:** Implemented highly scalable video upload, transcoding, and streaming pipelines leveraging S3, AWS MediaConvert (HLS), and CloudFront, driven by queued jobs and SNS webhook callbacks.
*   **Payments & Integrations:** Integrated comprehensive Stripe payment flows for subscriptions, invoicing, and webhook-driven billing, utilizing Lambda-proxied webhook verification.

---

## 🚀 Selected Projects & Platforms Developed

### 1. Job-Matching Platform with Video Profiles (Backend & Cloud Lead)
*   **Tech:** Laravel 12, PHP 8.2, MySQL, Redis, AWS, Flutter/React clients (2023–2026)
*   Sole principal author of the API serving Flutter iOS/Android apps and a React web client.
*   Architected the async layer: SQS-backed queue jobs and a dedicated batch tier running Laravel's scheduler under Supervisor, with ASG leader election.
*   Built a robust video pipeline (MediaConvert → HLS), Stripe subscriptions, Elasticsearch-backed corporate search, FCM push, and Pusher real-time messaging.
*   Wrote the AWS CDK stacks and CodePipeline/CodeDeploy release process for dev/staging/prod environments.

### 2. SaaS Automation Agent Platform (Backend & Infrastructure Owner)
*   **Tech:** Django 6, DRF, PostgreSQL 16, Terraform, Dify (2026)
*   Sole author of the API and Terraform infrastructure for a platform automating routine SaaS operations via agent workflows.
*   Implemented Procrastinate (Postgres-as-queue) for dynamic workflow cron schedules.
*   Built LINE Messaging API webhook handling and OIDC account linking, alongside a human-in-the-loop approval workflow.
*   Provisioned the AWS environment in Terraform and deployed a self-hosted Dify agent engine on ECS.

### 3. Multi-Agent Sales & Knowledge Assistant (Backend & AI Engineer)
*   **Tech:** Django REST, FastAPI, LangGraph/Agno, Weaviate, Celery, AWS (2025–2026)
*   Contributed to the core Django API and agent service of an internal AI assistant for a Japanese optics manufacturer.
*   Built an orchestrator-plus-specialist agent topology (product, SQL, web-search, emailer) over OpenAI/Anthropic models via LiteLLM, with RAG grounded in Weaviate.
*   Built the Celery-on-SQS async layer for meeting summarization and authored the AWS CDK infrastructure.

### 4. Leather Repair Estimation AI (AI/ML & Backend)
*   **Tech:** FastAPI, PyTorch (ViT), OpenAI, AWS (2025)
*   Built services around a Vision Transformer damage-detection model and a product classifier, combined with GPT-based brand detection to produce automated repair cost estimates.
*   Contributed to the ETL pipeline for training data and authored the AWS CDK stack.

### 5. Store Marketing & MEO SaaS (Backend Engineer)
*   **Tech:** Laravel, React, MySQL, AWS (2021–2024)
*   Contributed heavily to a large multi-tenant marketing platform (12,000+ commits).
*   Delivered Rakuten SMS API integrations and automated syncs spanning Google Business Profile, Instagram, LINE, and Google Ads, alongside LLM-assisted content generation.

### 6. Nirbaan Express Courier (Freelance Project)
*   **Tech:** Flutter, Dart, PHP, Laravel
*   Developed and deployed a full cross-platform e-courier software application spanning Web, Android, and iOS.

---

## 🧠 Developer Profile & Engineering Philosophy (LLM Context)

### AI-Assisted Development Workflow
*   **Primary Engine:** I rely heavily on **Claude Code** for deep architectural work, complex refactoring, and writing Infrastructure as Code (AWS CDK/Terraform).
*   **Parallel Problem Solving:** I run **OpenAI (ChatGPT)** and **Google Gemini** concurrently for quick syntax lookups, edge-case brainstorming, and comparing alternative approach trade-offs without breaking context in Claude.
*   **PR Submission:** I feed local diffs into Claude Code to catch missing error handlers, race conditions, or IAM privilege issues before staging, and use it to auto-generate structured PR descriptions with QA instructions.

### Cloud Platform Preferences
*   **AWS (Primary):** My definitive choice for mission-critical production environments. I favor AWS due to its programmable infrastructure (AWS CDK in TypeScript) which prevents configuration drift, and its unmatched ecosystem synergy for event-driven routing (S3, SQS, SNS, Lambda, MediaConvert).
*   **GCP:** Utilized primarily for streamlined, developer-friendly API integrations (Google Speech-to-Text, GA4, Google Ads, Google Business Profile).

---

## 🎓 Education & International Achievements

### **Military Institute of Science and Technology (MIST)**
*B.Sc in Computer Science & Engineering (CSE)* | Dhaka, Bangladesh | 2019 – 2023
*   **CGPA:** 3.69 / 4.00

### **Major Robotics & International Awards**
*   **Champion:** University Rover Challenge 2021, USA (Served as Software and Communication Team Lead, building the Mars rover and representing Bangladesh).
*   **2nd Runner-up:** Anatolian Rover Challenge (ARC) 2022, Istanbul, Turkey.
*   **Top 100:** MUJIB 100 Idea Contest at the International Conference on 4th Industrial Revolution (out of 1000+ teams).
*   **1st Runner-up:** Mobile App Contest, Inter University ICT Innovation Fest 2021.

### **Competitive Programming & Problem Solving**
*   Solved over 1000 problems across various online judges (Leetcode, Codeforces, Codechef, UVA, HackerRank).
*   **ACM ICPC Asia Dhaka Regional:** MIST_EndGame (76th in 2022), MIST_ThreeHorseman (76th in 2021).
*   **Leadership:** Mentor & General Secretary of MIST Computer Club (2020–2022), teaching Data Structures, Algorithms, and acting as a problem-setter for competitive programming contests.