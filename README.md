<h1 align="center">Will (anjggti)</h1>

<h3 align="center">Cloud Engineer — Terraform · Kubernetes · GitOps · Observability</h3>

<p align="center">
  I build platforms that stay up, stay observable, and stay inside a budget you can defend.
</p>

---

### What I do

- **Infrastructure as Code** — Terraform modules with remote state, plan gates in CI via OIDC,
  and cost guardrails (`check_no_nat`, budget alarms) treated as tests, not wishes.
- **Kubernetes & GitOps** — k3s on AWS spot instances, ArgoCD app-of-apps, Helm values pinned
  in Git: what's in the repo is what runs in the cluster.
- **Observability** — Prometheus + Grafana + Loki/Alloy end to end: ServiceMonitors, alert
  rules as code, dashboards as ConfigMaps, and an app that exports real business metrics.
- **Security in the pipeline** — zero static credentials, Trivy image gates, kubeconform strict
  on every manifest, no SSH (SSM only), runtime containers non-root with read-only rootfs.

### Featured work

| | | |
|:--:|---|---|
| 🌐 | **[netvision-platform](https://github.com/anjggti-eng/netvision-platform)** | Observability platform on AWS: Terraform + k3s (spot) + ArgoCD + Prometheus/Grafana/Loki. No NAT, no EKS — a **US$5/month budget alarm** instead of a surprise bill. |
| 📡 | **[NetVision](https://github.com/anjggti-eng/NetVision)** | Network observability for corporate MikroTik + Omada environments — collectors, metrics and dashboards for uplink health. |
| 🧾 | **[fiscalguard-pro](https://github.com/anjggti-eng/fiscalguard-pro)** | Fiscal analysis platform: FastAPI + Celery + PostgreSQL with JWT auth, rate limiting and full Prometheus instrumentation. |
| ⚓ | **[port-pilot](https://github.com/anjggti-eng/port-pilot)** | Swiss-army knife for local dev: port manager, HTTP analyzer, public tunnel and workspace auditor. |

### Principles I ship with

```text
cost is a feature       US$5 budget alarm instead of a surprise bill
state lives in Git      hand-edited clusters are drift, not configuration
credentials expire      OIDC federation, SSM sessions — nothing standing
gates or it didn't      tflint · terraform validate · kubeconform · vitest · trivy
cattle, not pets        node dies → ASG replaces it → ArgoCD re-syncs everything
```

### Stack

`Terraform` · `AWS` · `k3s / Kubernetes` · `ArgoCD` · `Helm` · `Prometheus` · `Grafana` ·
`Loki / Alloy` · `GitHub Actions` · `TypeScript / Node` · `FastAPI / Python` ·
`Docker` · `RouterOS / MikroTik`

### Now

Building **[netvision-platform](https://github.com/anjggti-eng/netvision-platform)** —
a portfolio-grade reference for running a real observability stack on near-zero cloud cost.

---

<p align="center">
  <a href="https://github.com/anjggti-eng">github.com/anjggti-eng</a> ·
  <a href="https://williamjohn.space">williamjohn.space</a>
</p>
