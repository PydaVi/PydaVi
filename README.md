# Fabio Souza

Cloud & Security Engineer. Building things to understand them.

AWS (SAA + CCP) · Fortinet · Kubernetes · Go · Terraform · EDR/SIEM

---

## Projects

### [witness](https://github.com/PydaVi/witness)
HTTP/1.1 reverse proxy written in Go from scratch — no frameworks, no abstractions.

Every layer built to understand what production infrastructure actually does underneath: TCP accept loops, manual HTTP/1.1 parsing, concurrent load balancing with mutex-safe round-robin, circuit breakers as state machines, TLS termination.

The differentiator is **Narrative Mode** — instead of emitting raw metrics, witness observes traffic patterns over time and surfaces what it notices in plain language, before it becomes a problem:

```
[narrative] backend-api is responding 40ms above the 2h baseline.
            Still within threshold, but trending worse since 14:30.

[narrative] 5xx rate on /api/checkout rose from 0.2% to 1.8% in the last 5min.
            Similar pattern preceded the last degradation window (2025-03-01 02:14).
```

`Go` `TCP` `HTTP/1.1` `Observability` `Circuit Breaker` `TLS`

---

### [brainctl](https://github.com/PydaVi/brainctl)
Declarative infrastructure CLI in Go — YAML contracts generate validated Terraform workspaces dynamically.

Functional MVP. Provisions EC2 workloads and self-managed Kubernetes clusters on AWS with observability, recovery, and security guardrails built in by default. Not a wrapper — opinionated guardrails block inconsistent configurations before they reach Terraform.

```yaml
workload:
  type: ec2-app
lb:
  enabled: true
observability:
  enabled: true
recovery:
  enabled: true
```

`Go` `Terraform` `AWS` `Platform Engineering` `IaC` `CloudWatch` `DLM`

---

### [brain-chaos](https://github.com/PydaVi/brain-chaos)
Kubernetes lab for learning cloud native security, chaos engineering, and GitOps hands-on.

Local k3d cluster with ArgoCD GitOps, full observability stack (Prometheus + Grafana + Loki + kube-state-metrics), and a CI/CD pipeline with manifest validation, Kyverno policy checks, and Trivy scanning. Built to simulate real attacks and failures against a synthetic e-commerce app — with documented detection, containment, and remediation for each scenario.

`Kubernetes` `ArgoCD` `Kyverno` `Trivy` `Prometheus` `Loki` `Chaos Engineering` `GitHub Actions`

---

## Currently

Working as Infrastructure & Cybersecurity Analyst at Suhai Seguradora — cloud environments, network security (FortiGate/Fortinet), EDR/SIEM operations, AWS architecture.

Building toward Cloud Native Security Engineer — supply chain security, runtime security (Falco/eBPF), network policy (Cilium), and everything that happens between `git push` and a pod running in production.

---

[LinkedIn](https://www.linkedin.com/in/fabio-souza-2464a81a9) · augustt.fabio@gmail.com
