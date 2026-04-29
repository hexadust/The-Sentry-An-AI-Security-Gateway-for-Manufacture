# 🛡️ The Sentry  
### AI Security Gateway for Manufacturing Systems

> An AI-powered IoT security gateway that detects phishing, malware, and social engineering threats in real-time before they reach industrial systems.

---

## 🔥 Overview

**The Sentry** is an AIoT-based cybersecurity system designed for manufacturing environments.  
It acts as a **first-layer security gateway** that analyzes emails, files, and links before they enter production systems.

Using **Machine Learning, NLP, and sandbox analysis**, the system provides real-time threat detection and automated decision-making.

---

## ⚙️ System Architecture

```mermaid
flowchart LR
A[Email / File / Link Input] --> B[Raspberry Pi Edge Gateway]
B --> C[AI/ML Static Analysis]
C --> D{Threat Detection}
D -->|Safe| E[Forward to Production System]
D -->|Suspicious| F[Docker Sandbox Analysis]
F --> G[Risk Evaluation Engine]
G --> H[Web Dashboard + Alert System]
