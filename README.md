# Marc Bourrel aka. Joo

DevOps & Cloud Architect freelance. Founder of [Joopin's Lab](https://joopinslab.com). Based in Toulouse.

10 years on critical infrastructure. The systems I work on can't go down.

My take: production incidents don't happen because of missing technology. They happen because of missing reliability, visibility, and structure. That's what I fix.

---

## TokenVeil

My main project right now. A self-hosted proxy that lets teams use Claude, ChatGPT or Gemini without handing over their data.

It replaces names, phone numbers, emails, IPs, IBANs and secrets with reversible tokens before anything leaves your network, then restores the real values in the reply. The mapping stays encrypted on your own server, so the AI provider never sees a real value. It stays reversible, so you keep a normal workflow.

Open core under the Elastic License, with a commercial engine that also catches names and organizations in free text. Docker, self-hosted, works with Claude, Gemini, OpenAI, Mistral and a few more. It ships a versioned REST API so you can plug anonymization into your own pipeline.

[tokenveil.eu](https://tokenveil.eu) · [docs](https://docs.tokenveil.eu) · [tokenveil-oss](https://github.com/Joopinhontas/tokenveil-oss)

---

## Setlist

The project I care most about. A music card game: you dig through crates, collect songs as cards, trade them with friends on a market, and settle it in blind test battles on a seasonal ladder.

SvelteKit 5 and PocketBase in a single container, French and English. Card rarity is scored from Deezer, Last.fm, Wikipedia and MusicBrainz signals. Blind tests have server-side anti-cheat, ranks run on ELO, and every release goes out through one script: backup, build, healthcheck, then patch notes posted to Discord.

[setlist.gg](https://setlist.gg) · private repo, happy to walk you through it

---

## What else I build

**Automation tools.** I use Claude API to build things I actually need. LinkedIn agent that posts every Monday without me touching it. Invoice processor that reads Gmail, classifies with a local LLM, and uploads to accounting. Claude Code hooks that back up files before AI touches them and block dangerous commands before they run.

**Infrastructure.** Kubernetes, Docker Swarm, OpenStack, VMware Tanzu. Azure when the client needs it. GitLab CI pipelines hardened from the start, not patched after an incident.

**Observability.** Grafana, Prometheus, Loki. I don't guess what's broken. I see it.

---

## Projects

| | |
|---|---|
| [homelab-platform](https://github.com/Joopinhontas/homelab-platform) | A self-hosted platform end to end: Traefik provisioned with Terraform, Ansible hardening, Prometheus / Loki / Grafana monitoring, CI on every push. |
| [tokenveil-oss](https://github.com/Joopinhontas/tokenveil-oss) | Reversible data anonymization for LLMs. Self-hosted, Docker, multi-AI. |
| [lire](https://github.com/Joopinhontas/lire) | Self-hosted manga and comics library manager for Kavita. Multi-arch image on GHCR, CI that boots the container before every release, hardened runtime, FR/EN. |
| [claude-code-hooks](https://github.com/Joopinhontas/claude-code-hooks) | Ready-to-use hooks for Claude Code: auto-backup, guard, notifications |
| [claude-repo-audit](https://github.com/Joopinhontas/claude-repo-audit) | Grade any Git repo: secret leaks, hygiene, and a Vibe Score. Claude skill + zero-dep scanner. |
| [linkedin-agent](https://github.com/Joopinhontas/linkedin-agent) | Autonomous LinkedIn posting via Claude API. Costs $2/year. |
| [factures-agent](https://github.com/Joopinhontas/factures-agent) | Gmail to accounting pipeline. 100% local, zero cloud cost. |

---

## Stack

**Orchestration** `Kubernetes` `Docker` `Docker Swarm` `VMware Tanzu` `OpenStack` `Helm`

**IaC & CI/CD** `Terraform` `Ansible` `GitLab CI` `Azure DevOps` `Artifactory` `Cloud-Init`

**Observability** `Grafana` `Prometheus` `Loki` `Aria for Logs`

**Cloud & Security** `Azure` `Azure Key Vault` `Azure Security Center` `RBAC` `Network Policies` `Keycloak`

**AI & Automation** `Claude API` `Ollama` `Python` `FastAPI` `spaCy` `Presidio` `Shell`

**Networking** `Cisco` `StormShield` `VPN` `Intune` `Microsoft Defender`

---

## Elsewhere

[tokenveil.eu](https://tokenveil.eu) · [joopinslab.com](https://joopinslab.com) · [LinkedIn](https://linkedin.com/in/mbour1) · [Malt](https://www.malt.fr/profile/marcbourrel1)
