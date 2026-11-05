
# Devaraju Gunturu
### M.Tech Cybersecurity | AI Security | Adversarial Machine Learning | Trustworthy AI

**SASTRA Deemed University, Thanjavur, India**

Email: [devarajugunturu123@gmail.com](mailto:devarajugunturu123@gmail.com)  
Website: [techmugger.github.io](https://techmugger.github.io/)  
GitHub: [github.com/techmugger](https://github.com/techmugger)  
LinkedIn: [Devaraju Gunturu](https://www.linkedin.com/in/devaraju-gunturu-a8744b249)

---

## About Me

I am an M.Tech student specializing in Cybersecurity at SASTRA Deemed University, India, with an interest in developing secure, reliable, and intelligent machine-learning systems.

My research interests lie at the intersection of Artificial Intelligence and Cybersecurity, particularly adversarial machine learning, trustworthy AI, neural-network protection, and intelligent intrusion detection.

I am interested in understanding how machine-learning systems can be exploited, how their reliability and ownership can be protected, and how AI-driven security mechanisms can improve the detection and analysis of threats in networked and IoT environments.

My current research direction is focused on three interconnected areas:

1. Adversarial Machine Learning and AI Security
2. Trustworthy AI and Neural-Network Protection
3. AI-driven Network and IoT Security

This repository provides an overview of my research interests, selected implementations, and technical work.

---

# Research Interests

## 1. Adversarial Machine Learning and AI Security

I am interested in studying adversarial threats against machine-learning systems, particularly how generative models and adversarial manipulation can affect the reliability of AI-based security mechanisms.

Research directions:
- Adversarial evasion attacks against machine-learning models.
- GAN-based adversarial sample generation.
- Robustness evaluation of machine-learning-based intrusion detection systems.
- Defensive mechanisms against adversarial manipulation.
- Security and reliability of AI-driven detection systems.

**Related research direction:** GAN-based adversarial evasion and defense for network intrusion detection.

---

## 2. Trustworthy AI and Neural-Network Protection

My interest in trustworthy AI includes protecting machine-learning models against unauthorized usage, replication, and ownership violations.

I am particularly interested in watermarking mechanisms that establish model ownership while maintaining model functionality and enabling reliable user traceability.

Research directions:
- Deep neural-network watermarking.
- Trigger-based model ownership verification.
- Generative-model-based watermark generation.
- Model protection and intellectual property verification.
- Blockchain-assisted ownership and authorization mechanisms.
- Robustness of watermarks against model manipulation.

**Selected implementation:**
GAN-PCPT & ACPT – Conditional GAN-Based DNN Watermarking.

---

## 3. AI-driven Network and IoT Security

I am interested in developing intelligent security architectures for networked and IoT environments, combining machine learning, network monitoring, and automated security analysis.

Research directions:
- Machine-learning-based network intrusion detection.
- IoT and cyber-physical systems security.
- Multi-stage threat detection and analysis.
- Agentic AI for security operations.
- Network traffic monitoring and behavioral analysis.
- Explainable and intelligent security monitoring systems.

**Selected implementations:**
- IoT Intrusion Detection Centric Agentic AI.
- Live IT/OT Network IDS using Zeek and ClickHouse.

---

# Selected Research Projects and Implementations

## 1. GAN-PCPT & ACPT: Conditional GAN-Based DNN Watermarking

**Repository:** [github.com/techmugger/gan-pcpt-acpt](https://github.com/techmugger/gan-pcpt-acpt)

**Research area:** Trustworthy AI | Neural-Network Security | Model Ownership Verification

### Research Overview

This project investigates scalable ownership verification and intellectual property protection for deep neural networks using a Conditional Generative Adversarial Network (cGAN)-based watermarking framework.

The implementation extends PCPT-style DNN watermarking by addressing the limitations of conventional trigger generation approaches, particularly the difficulty of distinguishing individual users when trigger sets contain highly similar samples.

### Key Components

- Conditional GAN-based generation of synthetic, user-specific trigger sets.
- PCPT-style neural-network watermark embedding.
- ACPT-based active authorization control.
- Blockchain-backed intellectual property lifecycle management.
- User traceability and ownership verification.
- Evaluation of scalability across multiple user configurations.

### Experimental Evaluation

The repository reports:

- User traceability evaluation at N = 2, 5, 10, and 20.
- 100% trace accuracy across the evaluated user configurations.
- Zero false-positive rate in the reported experiments.
- A seven-transaction blockchain IP lifecycle.
- Improved trigger diversity compared with the video-frame-based baseline.

### Technologies

Python | Deep Learning | Conditional GAN | DNN Watermarking | Blockchain | Jupyter Notebook

**Implementation:** [View source code and experiments](https://github.com/techmugger/gan-pcpt-acpt)

---

## 2. IoT Intrusion Detection Centric Agentic AI

**Repository:** [github.com/techmugger/iot-ids-agent](https://github.com/techmugger/iot-ids-agent)

**Research area:** IoT Security | Network Intrusion Detection | Agentic AI

### Research Overview

This project implements an IoT intrusion detection framework with auxiliary conversational capabilities.

It explores the integration of conventional machine-learning-based intrusion detection with an agentic AI architecture capable of processing security-related queries and coordinating different tools.

The implementation is organized into two distinct tracks.

### Track A – Machine-Learning-Based Intrusion Detection

- XGBoost-based intrusion classification.
- UNSW-NB15 as the primary dataset.
- NSL-KDD as a secondary benchmark.
- Data preprocessing and feature transformation.
- Model training and evaluation through Jupyter Notebook and Python modules.

### Track B – Agentic Conversational Security System

- LangGraph-based multi-LLM orchestration.
- Planner, executor, and evaluator architecture.
- Integration of intrusion-checking tools.
- Security-query triage and orchestration.
- FastAPI-based application interface.
- Optional Google Calendar and Gmail integrations.

### Technologies

Python | XGBoost | Scikit-learn | LangGraph | Large Language Models | FastAPI | Jupyter Notebook

**Implementation:** [View source code and project structure](https://github.com/techmugger/iot-ids-agent)

---

## 3. Live IT/OT Network IDS – Zeek, ClickHouse and Semantic SIEM Console

**Repository:** [github.com/techmugger/network-ids-zeek-chromadb](https://github.com/techmugger/network-ids-zeek-chromadb)

**Research area:** Network Security | Intrusion Detection | Security Monitoring | IT/OT Security

### Project Overview

This project implements a self-hosted network intrusion detection and security monitoring platform designed for mixed IT and OT environments.

It integrates live network traffic monitoring, centralized event storage, vulnerability correlation, and security monitoring interfaces into a containerized architecture.

### Architecture and Components

**1. Network Traffic Monitoring**
- Zeek-based live network traffic capture.
- Network connection and protocol analysis.
- Monitoring of IT and OT network traffic.

**2. Centralized Data Management**
- ClickHouse-based storage.
- Ingestion of network monitoring logs.
- Centralized storage of alerts, assets, and security observations.

**3. Threat Intelligence and Correlation**
- CVE matching using NVD reference data.
- MITRE ATT&CK technique correlation.
- Fuzzy and semantic matching for security analysis.

**4. Security Management Interface**
- FastAPI-based administrative console.
- Streamlit-based monitoring dashboard.
- Asset and alert management.
- Analyst actions: Allow, Block, and Investigate.
- Audit logging of alert-response decisions.

**5. Deployment Architecture**
- Docker Compose-based service orchestration.
- Nginx reverse proxy.
- Live network capture through a monitoring interface.
- Modular services for ingestion, monitoring, and administration.

### Technologies

Zeek | ClickHouse | Python | FastAPI | Streamlit | Docker | Docker Compose | Nginx | Network Security | MITRE ATT&CK | NVD

**Implementation:** [View source code and architecture](https://github.com/techmugger/network-ids-zeek-chromadb)

*Note: The response-action workflow currently includes a pluggable enforcement interface; actual firewall enforcement is not yet implemented.*

---

# Technical Skills and Research Tools

### Programming and Development
- Python
- Jupyter Notebook
- Git and GitHub

### Machine Learning and Artificial Intelligence
- Machine Learning
- Deep Learning
- XGBoost
- Generative Adversarial Networks
- Conditional GANs
- Adversarial Machine Learning
- Neural-Network Watermarking
- Explainable and Trustworthy AI

### Cybersecurity
- Network Intrusion Detection
- Network Traffic Analysis
- IoT Security
- IT/OT Security Monitoring
- Adversarial Security
- Vulnerability and Threat Intelligence
- MITRE ATT&CK

### Frameworks and Infrastructure
- Scikit-learn
- LangGraph
- FastAPI
- Zeek
- ClickHouse
- Streamlit
- Docker and Docker Compose
- Blockchain-based verification

---

# Education

**Master of Technology (M.Tech) – Cybersecurity**

SASTRA Deemed University  
Thanjavur, Tamil Nadu, India

Expected completion: March 2027

---

# Research Goals

My long-term research goal is to contribute to the development of secure, robust, and trustworthy AI systems.

I am particularly interested in pursuing doctoral research in:

- Adversarial machine learning and AI security.
- Trustworthy and robust machine learning.
- Neural-network watermarking and model protection.
- AI-driven network and IoT security.
- Intelligent and explainable intrusion detection.

I am interested in research opportunities that combine rigorous experimental evaluation with practical cybersecurity applications.

---

# Contact and Professional Profiles

- **Email:** [devarajugunturu123@gmail.com](mailto:devarajugunturu123@gmail.com)
- **Website:** [https://techmugger.github.io/](https://techmugger.github.io/)
- **GitHub:** [https://github.com/techmugger](https://github.com/techmugger)
- **LinkedIn:** [https://www.linkedin.com/in/devaraju-gunturu-a8744b249](https://www.linkedin.com/in/devaraju-gunturu-a8744b249)

---

*This repository serves as a research portfolio documenting selected implementations, technical explorations, and research interests in AI Security and Cybersecurity.*
