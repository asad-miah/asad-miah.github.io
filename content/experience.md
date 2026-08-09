---
title: Experience
---

## [Rhesis AI GmbH](https://rhesis.ai/): Backend & Infrastructure Engineer
**Aug 2025 – Present · Germany**

**Infrastructure & Platform:**
- Contributing to [Rhesis](https://github.com/rhesis-ai/rhesis), an open-source GenAI testing platform that enables cross-functional teams to design and automate quality validation for AI applications collaboratively.
- Provisioned all GCP infrastructure (GKE, networking, IAM, storage) using Terraform, deploying consistently across 3 isolated GCP projects.
- Implemented a GitOps delivery pipeline using ArgoCD with the App of Apps pattern, enabling fully automated deployments triggered end-to-end via GitHub Actions.
- Designed and maintained Helm-based Kubernetes deployment workflows for 10+ microservices across dev, staging, and production.
- Configured Kubernetes-native ingress routing using kGateway and HTTPRoute, and deployed WireGuard VPN with BIND9 as internal DNS for secure developer access.
- Deployed PostgreSQL using a tiered strategy — Helm subchart for dev, CloudNativePG Operator for staging/production — with automatic failover and continuous backup.
- Eliminated manual secrets/certificate management by integrating External Secrets Operator with GCP Secret Manager and cert-manager with Let's Encrypt.
- Deployed a production observability stack (Prometheus, Loki, Alloy, Grafana) with custom OpenTelemetry instrumentation across all environments.
- Designed and deployed a custom containerized 8B-parameter LLM on Vertex AI using vLLM (8-bit quantization), reducing inference latency by 40%.
- Investigated and resolved Kubernetes production issues including pod crashes, container failures, and ingress routing problems.
- Diagnosed and resolved Linux runtime issues affecting containerized Kubernetes workloads.

**Backend Development:**
- Developed task management features in a FastAPI backend, including entity modeling, REST APIs, validation logic, and asynchronous notifications.
- Designed and implemented comment and configuration services with multi-entity support and LLM-powered configuration generation.
- Built and deployed a Python-based LLM inference service with authentication, rate limiting, and batch processing.
- Optimized backend performance by tuning database connection pools and standardizing migrations.

---

## [Mitigant GmbH](https://mitigant.io/de): Backend Engineer
**Feb 2022 – Feb 2025 · Germany**
- Designed and implemented a Cloud Attack Emulation SaaS platform offering 50+ cloud attack scenarios to assess and improve customers' AWS and Azure cloud security posture, based on the MITRE ATT&CK and ATLAS frameworks.
- Built backend microservices in Java (Spring Boot) using Infrastructure as Code (IaC) to provision and securely access AWS and Azure environments.
- Architected a RabbitMQ-based messaging backbone to decouple 8 microservices, enabling asynchronous, event-driven communication and supporting zero-downtime multi-cloud deployments.
- Took full ownership of the Azure cloud attack emulation feature from design to deployment and monitoring, helping attract multi-cloud enterprise customers to the platform.
- Integrated Amazon Bedrock APIs to implement GenAI-based attack simulations, strengthening AI security evaluation in production systems.
- Integrated AWS CloudTrail, Amazon GuardDuty, and Datadog to enable real-time monitoring, observability, and evidence collection during simulated cloud attacks.
- Implemented comprehensive unit and integration tests using JUnit and Mockito, achieving over 80% code coverage and improving system reliability.
- Used Redis for caching and real-time user status tracking to deliver simulation reports to customers when online.
- Collaborated with the frontend team to design APIs supporting dynamic configuration of attack scenarios and real-time feedback during simulations.
- Conducted peer code reviews enforcing clean architecture principles, reducing integration issues and improving production deployment stability.

---

## [Hasso Plattner Institute](https://hpi.de/): Student Assistant
**Jul 2021 – Feb 2022 · Germany**

- Designed and developed the frontend and backend of a web application to process and visualize data.
- Processed and modeled data using Java and Gson, storing it in PostgreSQL for efficient querying and backend performance.
- Developed an interactive React/JavaScript frontend with advanced filtering and pagination, reducing load time by 50%.
- Implemented backend caching strategies using Redis to improve response times for frequently accessed data, resulting in a 40% reduction in database load.

---

## [BRAC University](https://www.bracu.ac.bd/): Full-stack Engineer
**Dec 2017 – May 2021 · Bangladesh**

- Developed new features for the University Student Information System — including online admission, student advising, accounts, and grade submission — supporting over 20,000 students.
- Optimized backend performance using HikariCP connection pool tuning, database indexing, and Redis caching to handle peak system load, improving response times by 30%.
- Designed and implemented a role-based access control (RBAC) system to manage user permissions and enhance security across the application.
- Implemented an audit trail system using Spring Security to track access and changes to sensitive data such as student payments and grades.
- Integrated payments via the SSLCommerz payment gateway, reducing manual processing errors by 30%.
- Built responsive JSP/HTML/CSS interfaces integrated with Groovy/Grails backend services for scalable web applications.

---

## CS InfoTech Ltd.: Full-stack Engineer
**Dec 2016 – Dec 2017 · Bangladesh**

- Delivered full-stack features for an automated loan-management application using Java, Spring Boot, Hibernate (JPA), and MySQL on the backend, and Thymeleaf on the frontend.
- Designed and implemented a credit scoring module that processed over 1,000 applications per month, improving risk assessment consistency and decision-making speed.
- Integrated the LogiDoc document management system, cutting document retrieval time by 60% and digitizing workflows.
- Implemented a notification system using Spring Boot and JavaScript to automate loan status updates, improving customer communication and reducing manual follow-ups.
- Applied Test-Driven Development (TDD) and wrote unit tests using JUnit to ensure correctness and maintainability of backend modules.
