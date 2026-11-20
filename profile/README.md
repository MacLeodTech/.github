# MacLeodTech

Welcome! This is where I build my projects and ideas: homelab tooling, security and infrastructure experiments, self-hosted apps, and the occasional side project that scratches a personal itch.

Most of what's here started as a problem I wanted solved for myself, then got cleaned up enough to share. Everything is a work in progress, so expect rough edges, and feel free to open an issue or poke around.

## Projects

### Self-hosted & homelab

| Project | What it is | Language |
|---|---|---|
| [**CrowsNest**](https://github.com/MacLeodTech/CrowsNest) | Web dashboard for starting, stopping and watching game server containers on a home server. Servers stop themselves when nobody's on. | Go |
| [**crowsnest-modules**](https://github.com/MacLeodTech/crowsnest-modules) | Game modules for CrowsNest. One YAML file per game, no code. | Shell |
| [**runner-scaling**](https://github.com/MacLeodTech/runner-scaling) | Ephemeral, autoscaled GitHub Actions runners on a single Docker host, with a no-network guard holding the Docker socket. | Go |
| [**AiGateway**](https://github.com/MacLeodTech/AiGateway) | Self-hosted, OpenAI-compatible AI proxy for home labs, with secrets scanning, PII redaction, cost and rate limits, and upstream failover. | Go |
| [**Topiary**](https://github.com/MacLeodTech/Topiary) | Self-hosted training platform for learning development and operational workflows-as-code. | Python |

### AI

| Project | What it is | Language |
|---|---|---|
| [**Aegis**](https://github.com/MacLeodTech/Aegis) | Terminal-first AI agent harness for security, architecture, research and development. Built in Go, designed around local LLMs, with cloud providers optional. | Go |

### Security & cloud infrastructure

| Project | What it is | Language |
|---|---|---|
| [**BastionOnDemand**](https://github.com/MacLeodTech/BastionOnDemand) | On-demand Azure Bastion with layered Entra ID, Just-in-Time and Bastion access. IaC and automation reference implementation. | Python |
| [**dns-as-code-template**](https://github.com/MacLeodTech/dns-as-code-template) | Template for DNS-as-Code with dnscontrol and Cloudflare, with a PR-based preview/apply workflow. | Python |
| [**appsectools**](https://github.com/MacLeodTech/appsectools) | Downloads Azure DevOps Advanced Security alerts (code, dependency, secret) for a repo and branch and exports them to CSV. | Python |
| [**PanToGithubEDL**](https://github.com/MacLeodTech/PanToGithubEDL) | Pull a Palo Alto External Dynamic List directly from GitHub. | Python |

### Utilities

| Project | What it is | Language |
|---|---|---|
| [**SonarUpdater**](https://github.com/MacLeodTech/SonarUpdater) | Automatically switches your SteelSeries Sonar audio EQ profile when you launch a new game on Steam. | Python |
| [**TeacherGradeBookReports**](https://github.com/MacLeodTech/TeacherGradeBookReports) | Turns a spreadsheet matrix of students × assignments into gradebook reports. | Rust |

## Get in touch

Found a bug or have an idea? Open an issue on the relevant repo.
