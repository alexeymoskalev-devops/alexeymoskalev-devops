<h1 align="center">Alexey Moskalev</h1>
<p align="center">
  <b>DevOps / SRE</b> · node & validator infrastructure for Web3
  <br>
  <sub>CI/CD · Containers · Observability · Multi-chain operations</sub>
</p>

<p align="center">
  <a href="https://github.com/alexeymoskalev-devops?tab=repositories"><img src="https://img.shields.io/badge/repos-public%20work-2b3137?style=flat-square&logo=github"></a>
  <img src="https://img.shields.io/badge/focus-DevOps%20%2F%20SRE-326ce5?style=flat-square">
  <img src="https://img.shields.io/badge/domain-Web3%20infra-6f42c1?style=flat-square">
  <!-- TODO: add Telegram / email / LinkedIn badges, e.g.:
  <a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/email-contact-d14836?style=flat-square&logo=gmail&logoColor=white"></a>
  -->
</p>

---

### Who I am

DevOps / SRE at **[NODERS]**, a professional node operator. I run and automate
validator and node infrastructure across multiple chains — building the CI/CD,
container delivery, and monitoring/automation that keep them healthy.

<!-- TODO: one honest line about scale — e.g. "Operate N validators across X networks"
     or "M+ years in DevOps". Keep it to numbers you can defend in an interview. -->

- 🌏 Based in Indonesia
- 🛠️ Day-to-day: GitHub Actions, Docker, GHCR, PM2, SSH-based deploys, Prometheus-style metrics
- ⛓️ Chains I work with: Cosmos, Sui, Solana, Story Protocol
- 🧰 Languages: TypeScript · Python · Rust · Go · Shell

---

### What I actually build (with proof)

**CI/CD I've written — not just "familiar with":**

| Repo | Pipeline | What it demonstrates |
|------|----------|----------------------|
| [`drmed_ai`](https://github.com/alexeymoskalev-devops/drmed_ai) | `lint → typecheck → build`, semver-tagged Docker release to GHCR | Job dependency chains, `docker/metadata-action`, release-on-tag |
| [`cosmos-voting-bot`](https://github.com/alexeymoskalev-devops/cosmos-voting-bot) | Build → SSH deploy → PM2 process management | Secrets handling, zero-tooling-on-host deploys |

**Node-operator tooling & observability:**

- [`cosmos-exporter`](https://github.com/alexeymoskalev-devops/cosmos-exporter) — scrape validator/wallet/chain metrics for the Cosmos network
- [`cosmos-voting-bot`](https://github.com/alexeymoskalev-devops/cosmos-voting-bot) · [`sui_voter`](https://github.com/alexeymoskalev-devops/sui_voter) — governance-vote automation for validators
- [`solana-validator-switch`](https://github.com/alexeymoskalev-devops/solana-validator-switch) — 1–2s hot-swap / failover for Solana validators

**Open-source Web3 infrastructure (Story Protocol):**

- [`story-subgraph`](https://github.com/alexeymoskalev-devops/story-subgraph) — The Graph subgraph indexing IP assets, license terms, derivative links & royalties — an open alternative to proprietary indexers
- [`story-ip-graph-mcp`](https://github.com/alexeymoskalev-devops/story-ip-graph-mcp) — MCP server for IP-graph ops (registration + lineage + royalty reads), verified on-chain on `aeneid`
- [`story-ip-explorer`](https://github.com/alexeymoskalev-devops/story-ip-explorer) — Next.js dashboard: ecosystem metrics + interactive IP-lineage explorer
- [`story-ip-agent-demo`](https://github.com/alexeymoskalev-devops/story-ip-agent-demo) — autonomous agent that registers derivative IP and reads lineage on-chain

---

### Toolbox

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

<!-- TODO: add only tools you genuinely use — e.g. Terraform, Ansible, Kubernetes,
     Grafana, Nginx, Cosmos SDK. Don't pad with logos you can't talk about. -->

---

### GitHub activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=alexeymoskalev-devops&show_icons=true&hide_border=true&theme=tokyonight&count_private=true">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alexeymoskalev-devops&layout=compact&hide_border=true&theme=tokyonight">
</p>

<!-- Stats are rendered live by github-readme-stats (third-party). Remove this block
     if you prefer not to rely on an external service. -->
