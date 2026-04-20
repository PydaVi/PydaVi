<img width="1440" height="2970" alt="image" src="https://github.com/user-attachments/assets/7eb052f5-2a84-4db9-94d2-687b2d6e73a4" />Fabio Souza
Cloud & Security Engineer. Building things to understand them.

AWS SAA + CCP
Fortinet
Kubernetes
Go
Terraform
EDR/SIEM
Projects

rastro
active
open-source · autonomous attack path validation engine for AWS
Rastro maps exploitable attack paths in AWS environments by combining live infrastructure state with automated reasoning — not synthetic fixtures. It enforces a strict separation of concerns: Scope Enforcer is inviolable, the LLM is a reasoning component not an orchestrator, and the Audit Logger is append-only. The engine validates real-world paths through multi-branch backtracking and path scoring, built on lessons from actual cloud security investigations.

# two-product strategy
produto 01  →  consultancy: real-world cases, revenue from day one
produto 02  →  CI/CD SaaS API: built on validated cases from P01
Go
AWS
CSPM
Attack Path Analysis
IAM
Cloud Security
witness
active
HTTP/1.1 reverse proxy in Go from scratch — no frameworks, no abstractions. TCP accept loops, manual HTTP/1.1 parsing, concurrent load balancing with mutex-safe round-robin, circuit breakers as state machines, TLS termination. The differentiator is Narrative Mode — instead of raw metrics, witness observes traffic patterns over time and surfaces what it notices in plain language, before it becomes a problem.

[narrative] backend-api is responding 40ms above the 2h baseline.
            Still within threshold, but trending worse since 14:30.
[narrative] 5xx rate on /api/checkout rose from 0.2% to 1.8% in the last 5min.
            Similar pattern preceded the last degradation window (2025-03-01 02:14).
Go
TCP
HTTP/1.1
Observability
Circuit Breaker
TLS
brainctl
active
Declarative infrastructure CLI in Go — YAML contracts generate validated Terraform workspaces dynamically. Provisions EC2 workloads and self-managed Kubernetes clusters on AWS with observability, recovery, and security guardrails built in by default. Not a wrapper — opinionated guardrails block inconsistent configurations before they reach Terraform.

yaml workload:
  type: ec2-app
  lb:            { enabled: true }
  observability: { enabled: true }
  recovery:      { enabled: true }
Go
Terraform
AWS
Platform Engineering
IaC
CloudWatch
DLM
brain-chaos
frozen until witness v0.3
Kubernetes lab for learning cloud native security, chaos engineering, and GitOps hands-on. Local k3d cluster with ArgoCD, full observability stack (Prometheus + Grafana + Loki), and CI/CD with manifest validation, Kyverno policy checks, and Trivy scanning. Built to simulate real attacks and failures against a synthetic e-commerce app — with documented detection, containment, and remediation for each scenario.

Kubernetes
ArgoCD
Kyverno
Trivy
Prometheus
Loki
Chaos Engineering
GitHub Actions
Currently

Infrastructure & Cybersecurity Analyst at Suhai Seguradora — cloud environments, network security (FortiGate/Fortinet), EDR/SIEM operations, AWS architecture. Building toward Cloud Native Security Engineer — supply chain security, runtime security (Falco/eBPF), network policy (Cilium), and everything that happens between git push and a pod running in production.

LinkedIn
augustt.fabio@gmail.com
github.com/PydaVi
