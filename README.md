# 👋 Hi, I'm Fabio Souza
> 📛 **PydaVi** comes from *Pai da Vi(tória)* – "Father of Vi(tória)", my daughter and biggest joy in life.

🔧 Infrastructure Analyst focused on **Cloud**, **Security**, and **Automation**  
🎓 Certifications: AWS Solutions Architect – Associate | AWS Cloud Practitioner | Fortinet Certified Associate  

---

## 🔭 Currently working with:
- Cloud environments (AWS)
- Infrastructure hardening, monitoring, and alerting
- Technical leadership in cloud and security projects

## 🌱 Continuously learning about:
- Secure and resilient cloud architecture design
- Platform Engineering and Golden Paths
- Infrastructure as Code
- Cloud governance, observability, and security automation

---

## 📌 Highlighted Projects

### 👁 [witness](https://github.com/PydaVi/witness)
**Programmable L7 Reverse Proxy with Narrative Observability**

`witness` is an HTTP/1.1 reverse proxy written in **Go from scratch** — no heavy frameworks, no abstractions hiding what's actually happening at the system level.

The project is built around a core frustration: proxies and firewalls make decisions constantly and stay silent about them. When something breaks, you're chasing logs full of noise and empty of context. The tool knew. It didn't tell you.

`witness` addresses this with **Narrative Mode** — instead of just emitting metrics and structured logs, it observes traffic patterns over time and surfaces what it notices, before it becomes a problem:

```
[narrative] backend-api is responding 40ms above the 2h baseline.
            Still within threshold, but trending worse since 14:30.

[narrative] 5xx rate on /api/checkout rose from 0.2% to 1.8% in the last 5min.
            Similar pattern preceded the last degradation window (2025-03-01 02:14).
```

Built incrementally across versioned milestones — from raw TCP listener and HTTP/1.1 parser to TLS termination, circuit breaking, and statistical anomaly detection — every layer is an opportunity to understand what production infrastructure is actually doing underneath.

> `witness` is actively evolving. It exists because understanding beats operating blindly.

---

### 🧠 [brainctl](https://github.com/PydaVi/brainctl)
**Declarative Infrastructure Control Plane (AWS + Terraform)**

`brainctl` is a **functional MVP CLI**, written in **Go**, designed to provision and manage AWS infrastructure using a **fully declarative YAML model**, with Terraform generated dynamically under the hood.

The project focuses on **Platform Engineering principles**, combining:
- **Governance and standardization** of cloud infrastructure
- **Reproducibility** through declarative definitions as a single source of truth
- **Observability and alerting** as first-class concerns
- **Security and cyber resilience** embedded into infrastructure patterns
- **Drift detection** to identify unmanaged changes

`brainctl` also acts as a **Golden Path**, guiding teams toward secure, observable, and compliant infrastructure by default, while still allowing controlled evolution.

> The project is actively evolving and serves as both a learning platform and a solid foundation for advanced platform and security capabilities.

---


### 🛰 [SOC Autônomo](https://github.com/PydaVi/soc-autonomo)
A lightweight, modular lab to analyze PCAP files with Zeek, Suricata, and Elastic SIEM.  
Designed to support cybersecurity learning and democratize access to powerful tools.

---

## 📫 Contact
- [LinkedIn](https://www.linkedin.com/in/fabio-souza-2464a81a9)  
- 📧 Email: augustt.fabio@gmail.com
