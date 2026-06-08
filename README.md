<h1 align="center">Alexey Moskalev</h1>
<p align="center">
  <b>DevOps / SRE Engineer</b>
  <br>
  <sub>Production infrastructure · Kubernetes · Observability · CI/CD · IaC</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/experience-4%2B%20years-2b3137?style=flat-square">
  <img src="https://img.shields.io/badge/focus-DevOps%20%2F%20SRE-326ce5?style=flat-square">
  <img src="https://img.shields.io/badge/scale-60%2B%20prod%20servers-1f6feb?style=flat-square">
  <!-- TODO: add contact badges — email / Telegram / LinkedIn, e.g.:
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/email-contact-d14836?style=flat-square&logo=gmail&logoColor=white"></a>
  -->
</p>

---

### Who I am

DevOps / SRE engineer with **4+ years** operating production infrastructure.
I run fleets of bare-metal and cloud servers, build observability and CI/CD from
scratch, and codify everything as IaC. I care about uptime, fast safe deploys,
and infrastructure you can reason about.

- 🌏 Based in Indonesia
- ☸️ Day-to-day: GCP/GKE, Kubernetes, Ansible, Prometheus/Grafana, Docker, GitHub Actions
- 🧰 I write tooling in **Python · Go · Bash**
- 🔧 On-call, incident response, postmortems — SRE practices, not just pipelines

---

### What I've done (with numbers)

**Infrastructure & operations**
- Operate **60+ production servers** across GCP (managed Kubernetes — **GKE**) and bare-metal in three European DCs (Hetzner, Vultr, OVH); migrated a large share of workloads from bare-metal into GKE.
- **Kubernetes in production:** Helm charts, sealed-secrets, cert-manager, NetworkPolicies, resource quotas, dev/staging/prod environments, per-namespace service isolation.

**Observability (built from zero)**
- Stack: **Prometheus · Grafana · Loki · Promtail · Alertmanager · Alerta** — **100% production alert coverage** routed to Telegram.
- Custom Prometheus exporters in **Python and Go**.

**CI/CD & automation**
- CI/CD on **GitHub Actions, GitLab CI, Semaphore CI** with zero-downtime deploys — **deploy time cut from ~30 min to ~3 min**.
- Multi-stage Docker builds, image optimization, publishing to **GHCR**.
- **Infrastructure as Code with Ansible** (roles, playbooks, dynamic inventory) — **new environment spin-up from ~2 h to ~15 min**.

**Networking & security**
- Nginx (reverse proxy, TLS, rate limiting), cert-manager for automated certificates, **Cloudflare** (WAF, DDoS protection, DNS, caching).
- Linux hardening: ufw/iptables, fail2ban, SSH policy (keys + jumphost), sealed-secrets, a security baseline on every node.

**Data & internal tooling**
- PostgreSQL & SQLite in production — deploys, schemas, backups, analytical SQL for operational metrics.
- Built an internal **Server Dashboard** — real-time monitoring UI for a fleet of **90+ servers** (Prometheus + Ansible inventory + service registry, live over WebSocket).

**SRE practices**
- On-call rotation, incident response, postmortems; deploy standards and code review for infrastructure code.

---

### Tech I work with

**Cloud & Orchestration**
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**IaC & CI/CD**
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A800?style=flat-square&logo=grafana&logoColor=white)

**Networking & Security**
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Data & Languages**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

### Open-source & side projects


A sample of public work — CI/CD pipelines and node/validator tooling I can show end-to-end:

- [`drmed_ai`](https://github.com/alexeymoskalev-devops/drmed_ai) — full GitHub Actions CI/CD: `lint → typecheck → build` + semver-tagged Docker releases to GHCR
- [`cosmos-voting-bot`](https://github.com/alexeymoskalev-devops/cosmos-voting-bot) — governance-proposal monitor, deployed via GitHub Actions over SSH with PM2
- [`cosmos-exporter`](https://github.com/alexeymoskalev-devops/cosmos-exporter) — Prometheus metrics for Cosmos validators/wallets (Go)
- [`sui_voter`](https://github.com/alexeymoskalev-devops/sui_voter) — SUI gas-price auto-voter daemon (Python)

<details>
<summary>Web3 infrastructure experiments (Story Protocol)</summary>

- [`story-subgraph`](https://github.com/alexeymoskalev-devops/story-subgraph) — The Graph subgraph indexing IP assets, license terms, derivative links & royalties
- [`story-ip-graph-mcp`](https://github.com/alexeymoskalev-devops/story-ip-graph-mcp) — MCP server for IP-graph ops, verified on-chain on `aeneid`
- [`story-ip-explorer`](https://github.com/alexeymoskalev-devops/story-ip-explorer) — Next.js dashboard for ecosystem metrics + IP lineage
- [`story-ip-agent-demo`](https://github.com/alexeymoskalev-devops/story-ip-agent-demo) — autonomous agent registering derivative IP on-chain

</details>


<!-- profile render nudge -->
