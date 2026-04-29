# The Sentry  
### AI Security Gateway for Manufacturing Systems

> An AI-powered IoT security gateway that detects phishing, malware, and social engineering threats in real-time before they reach industrial systems.

---

## Overview

**The Sentry** is an AIoT-based cybersecurity system designed for manufacturing environments.  
It acts as a **first-layer security gateway** that analyzes emails, files, and links before they enter production systems.

Using **Machine Learning, NLP, and Docker Container for sandbox analysis**, the system provides real-time threat detection and automated decision-making.

---

## Key Features & System Capabilities

- 🧠 **AI-Powered Threat Detection**
  Uses Machine Learning and NLP models to analyze emails, files, and links for phishing patterns and malicious content.

- 🧪 **Dynamic Sandbox Analysis**
  Suspicious inputs are executed inside isolated Docker containers to observe runtime behavior safely.

- ⚡ **Edge Security Gateway**
  Raspberry Pi 4 acts as a real-time security gateway that filters all incoming external data before reaching production systems.

- 🔐 **Automated Threat Classification**
  System automatically classifies input into SAFE or MALICIOUS categories based on AI-driven risk scoring.

- 🔔 **Physical Alert System**
  Integrates GPIO-based hardware (LED + buzzer) to trigger real-world security alerts when threats are detected.

- 📊 **Real-Time Security Dashboard**
  Web-based monitoring interface showing threat logs, system status, and risk analytics in real-time.

- ☁️ **Cloud & Notification Integration**
  Supports real-time alerts and logging via MQTT / cloud messaging services.

---

## 🧰 Technology Stack

- 🐍 **Python** – AI/ML models, backend logic, and threat analysis engine  
- 🧠 **Machine Learning & NLP** – Phishing detection and text classification  
- 🐳 **Docker** – Secure sandbox environment for dynamic analysis  
- 🍓 **Raspberry Pi 4** – Edge IoT security gateway  
- 🌐 **Flask / Node.js** – Backend API services  
- ⚛️ **React.js** – Web dashboard interface  
- 📡 **MQTT / REST API** – Real-time system communication  

---

## 🔄 System Workflow (Detailed)

1. External input (email, file, or link) enters the system  
2. Raspberry Pi processes input at the edge layer  
3. AI model performs static analysis (NLP/ML classification)  
4. If suspicious → input is sent to Docker sandbox for dynamic analysis  
5. System evaluates behavior and assigns risk score  
6. Decision engine determines output:
   - ✅ Safe → forwarded to production system  
   - ❌ Malicious → isolated + alert triggered  
7. Results are visualized on web dashboard in real-time  

---

## 📌 Industrial Use Case

The Sentry is designed for **manufacturing environments** where:
- High-volume external communication occurs (vendors, email, files)
- Legacy systems are vulnerable to phishing attacks
- Downtime from cyberattacks leads to high operational loss

It acts as a **pre-entry cybersecurity layer** to prevent threats before they reach critical systems.

---
