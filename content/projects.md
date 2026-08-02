---
title: Projects
---

Selected technical projects and contributions from my work and research.

---

## Rhesis: Open-Source LLM Testing Platform
`Python · TypeScript · Kubernetes · Terraform · ArgoCD`

Backend & infrastructure contributor to [Rhesis](https://github.com/rhesis-ai/rhesis), an open-source, MIT-licensed platform for collaborative testing of LLM and agentic applications — bringing engineers, PMs, and domain experts together to generate tests, simulate conversations, run adversarial red-teaming, and trace failures via OpenTelemetry. I own the platform's GCP infrastructure end-to-end: provisioning with Terraform, GitOps delivery via ArgoCD, Kubernetes deployment workflows for 10+ microservices, and a production observability stack (Prometheus, Loki, Grafana). I also deployed a custom containerized 8B-parameter LLM on Vertex AI using vLLM, reducing inference latency by 40%.

[GitHub →](https://github.com/rhesis-ai/rhesis)

---

## Cloud Attack Emulation Platform
`Java · Spring Boot · RabbitMQ · AWS · Azure`

Designed and implemented backend microservices for [Mitigant's Cloud Attack Emulation](https://mitigant.io/en/platform/cloud-attack-emulation) platform, which lets security teams safely run real, MITRE ATT&CK-mapped attacks to validate cloud defenses instead of relying on theoretical audits. I built the Java/Spring Boot services provisioning and securely accessing customer AWS and Azure environments via Infrastructure as Code, and architected a RabbitMQ-based messaging backbone decoupling 8 microservices for asynchronous, event-driven communication — supporting zero-downtime multi-cloud deployments across 50+ attack scenarios.

---

## University Student Information System
`Java · Redis · PostgreSQL · HikariCP`

Developed new features for BRAC University's Student Information System — including online admission, student advising, accounts, and grade submission — supporting over 20,000 students. Optimized backend performance using HikariCP connection pool tuning, database indexing, and Redis caching, improving response times by 30%.

---

## SUBEAT: N-of-1 Trials Toolbox
`Java · Apache OpenNLP · Java Swing`

Developed a Java-based framework and toolbox to enable flexible N-of-1 trials of smartphone usage behavior, built during my master's thesis at Hasso Plattner Institute. Used Apache OpenNLP and Regular Expressions to identify and anonymize sensitive entities (names, street names, etc.) from Android/iOS smartphone datasets, achieving 95% entity-recognition accuracy and ensuring HIPAA/GDPR compliance. Designed the GUI in Java Swing for flexible configuration and real-time anonymization.

[GitHub →](https://github.com/asad-miah/SUBEAT)
