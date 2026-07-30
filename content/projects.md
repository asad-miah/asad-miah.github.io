---
title: Projects
---
Selected technical projects and contributions from my work and research.

---
## SUBEAT: N-of-1 Trials Toolbox
`Java · Apache OpenNLP · Java Swing`
Developed a Java-based framework and toolbox to enable flexible N-of-1 trials of smartphone usage behavior, built during my master's thesis at Hasso Plattner Institute. Used Apache OpenNLP and Regular Expressions to identify and anonymize sensitive entities (names, street names, etc.) from Android/iOS smartphone datasets, achieving 95% entity-recognition accuracy and ensuring HIPAA/GDPR compliance. Designed the GUI in Java Swing for flexible configuration and real-time anonymization.
[GitHub →](https://github.com/asad-miah/SUBEAT)

---
## Cloud Attack Emulation Platform
`Java · Spring Boot · RabbitMQ · AWS · Azure`
Designed and implemented a Cloud Attack Emulation SaaS platform at Mitigant GmbH, offering 50+ cloud attack scenarios based on the MITRE ATT&CK and ATLAS frameworks to assess AWS and Azure security posture. Architected a RabbitMQ-based messaging backbone decoupling 8 microservices for asynchronous, event-driven communication, supporting zero-downtime multi-cloud deployments.

---
## Production Observability & Kubernetes Deployment
`Kubernetes · Helm · Prometheus · Loki · Grafana · CloudNativePG`
Designed Helm-based Kubernetes deployment workflows for 10+ microservices at Rhesis AI, enabling consistent releases across development, staging, and production. Deployed a full observability stack (Prometheus, Loki, Alloy, Grafana) and a tiered PostgreSQL strategy with automatic failover and continuous backup to GCP Cloud Storage.

---
## University Student Information System
`Java · Redis · PostgreSQL · HikariCP`
Developed new features for BRAC University's Student Information System — including online admission, student advising, accounts, and grade submission — supporting over 20,000 students. Optimized backend performance using HikariCP connection pool tuning, database indexing, and Redis caching, improving response times by 30%.
