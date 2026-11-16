<div align="center">

# Anas BENAMARA

**Software Engineering Student @ ENSIAS · Java Backend (Spring Boot) · Microservices · DevOps**

*Software & Data Sciences — Rabat, Morocco*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anas-benamara)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anasxaz)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:anas.benamara7@gmail.com)

</div>

---

## About Me

Final-year engineering student at **ENSIAS** (École Nationale Supérieure d'Informatique et d'Analyse des Systèmes), specializing in **Software & Data Sciences**. I focus on **Java backend development**: Spring Boot microservices, event-driven architecture, and deploying them with Docker, Kubernetes and CI/CD.

- Built **TicketFlow**, an incident management platform: 7 Spring Boot microservices, Kafka, Camunda 8, LLM-assisted triage, deployed on Kubernetes
- Built a **hospital management system** (5 user roles, 30+ REST endpoints, real-time SSE) during my internship at Intelcom
- Designed a **DevSecOps pipeline** with 9 jobs and 7 security tools (SAST, SCA, DAST, secret scan, container scan)
- **Salesforce Developer Intern @ D&A Technologies**: delivered Apex/LWC modules for a client in the French Energy Savings Certificates (CEE) sector

---

## Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring-security&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![Camunda](https://img.shields.io/badge/Camunda_8-FC5D0D?style=flat-square&logo=camunda&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)

### Frontend
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarcloud&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white)

### Databases
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

### Also
![Salesforce](https://img.shields.io/badge/Salesforce_(Apex,_LWC)-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

---

## Featured Projects

### [TicketFlow](https://github.com/anasxaz/ticketflow) — Incident management platform
> Java 21 · Spring Boot 4 · Spring Cloud · Kafka · Camunda 8 · Spring AI · Keycloak · Angular · Kubernetes

- **7 microservices** behind an API Gateway (JWT validation, role-based access with Keycloak, OAuth2 + PKCE)
- **Transactional Outbox** + Kafka with idempotent consumers: no lost or duplicated events
- **BPMN workflow** (Camunda 8): agent assignment, SLA timers, escalation, compensation, human triage task
- **Hybrid triage**: an LLM extracts facts from free text, ITIL rules compute the priority, humans correct it with an audit trail
- Integration tests with **Testcontainers**, CI/CD with **GitHub Actions** (8 images on GHCR), deployed on **Kubernetes**
- Observability with Prometheus, Grafana and Zipkin; design decisions documented in **8 ADRs**

### Hospital Management System — Intelcom
> Full stack internship project · React 19 + Spring Boot + MySQL + JWT/RBAC

- 5 user modules · 30+ secured REST endpoints · real-time SSE notifications
- Automatic PDF generation · interactive statistics dashboard (Recharts)

### DevSecOps Pipeline — ENSIAS
> GitHub Actions · 9 jobs · 7 security tools

- **SAST** (Semgrep) · **SCA** (npm audit) · **Secret scan** (Gitleaks)
- **Container scan** (Trivy) · **DAST** (OWASP ZAP) · **Quality gate** (SonarCloud)
- 36 security tests · 68% coverage · 60% fewer security issues after remediation

### Salesforce Developer Internship — D&A Technologies
> 2 months · Casablanca · client in the French Energy Savings Certificates (CEE) sector

- Account cloning with business rule validation and automated Chatter notifications (Apex + Flow)
- Contract management module: data model, validation rules, Lightning UI, LWC component with Apex controller, dashboards and unit tests

### Applied AI — Neuropsychiatric Classification
> Deep Learning + RL · UCLA fMRI dataset (ds000030) · 272 subjects

- 4-class classification (Control, Schizophrenia, Bipolar, ADHD) with 3D CNN and ResNet 3D built from scratch
- Multimodal fusion (fMRI + phenotypic data): **64.29% accuracy**

---

## Education & Certifications

- **Engineering Degree** — Data & Software Sciences (D2S), ENSIAS Rabat *(2024 – present)*
- **HashiCorp Terraform Associate** *(in preparation)*
- **Cisco CCNA 1** *(2026)*
- **Problem Solving (Basic) — HackerRank** *(2026)*
- **28 Salesforce Trailhead badges** — ~39,000 points *(2026)*

---

<div align="center">

*Open to a 6-month PFE internship starting February 2027 · Java Backend · Microservices · DevOps*

</div>
