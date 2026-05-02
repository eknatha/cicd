# ⚡ CICDLab — cicd.eknathalabs.com

> Master CI/CD & GitOps — GitHub Actions, ArgoCD, Pipelines.  
> Fully offline · Free forever · No signup · No ads · Built by a Platform Engineer.

---

## 🚀 Live Site

**[cicd.eknathalabs.com](https://cicd.eknathalabs.com)**

Part of the [EknathaLabs](https://eknathalabs.com) free learning platform:

| Lab | URL |
|-----|-----|
| 🐳 DockerLab | [docker.eknathalabs.com](https://docker.eknathalabs.com) |
| ☸ KubeLab | [kubelab.eknathalabs.com](https://kubelab.eknathalabs.com) |
| 🛰 Terraform | [terraform.eknathalabs.com](https://terraform.eknathalabs.com) |
| 🐧 LinuxLab | [linux.eknathalabs.com](https://linux.eknathalabs.com) |
| ⚡ CICDLab | [cicd.eknathalabs.com](https://cicd.eknathalabs.com) |

---

## 📦 What's Inside

A single-file HTML application — zero dependencies, zero build tools, zero backend.

### 8 Learning Modules

| Module | Level | Topics |
|--------|-------|--------|
| GitHub Actions Foundations | Beginner | Triggers, jobs, steps, runners, contexts, expressions |
| Secrets & Environments | Beginner | Secrets scope, OIDC auth to AWS/GCP/Azure, environment protection |
| Reusable Workflows & Actions | Intermediate | workflow_call, composite actions, matrix strategy, caching |
| Self-hosted Runners | Intermediate | Setup, security hardening, ephemeral runners, ARC |
| ArgoCD Core Concepts | Intermediate | Applications, sync phases, health checks, App of Apps, ApplicationSet |
| GitOps Patterns | Intermediate | Push vs pull model, Image Updater, multi-env promotion, Sealed Secrets |
| Pipeline Deployment Patterns | Advanced | Blue-green, canary, rolling, Argo Rollouts, automated rollback |
| Security & Supply Chain | Advanced | SLSA, cosign, SBOM, Sigstore, workflow hardening, dependency scanning |

### 8 Offline Interactive Tools

| Tool | Type | Description |
|------|------|-------------|
| **Workflow Generator** | Generator | Select stack + trigger → get production-ready `.github/workflows` YAML |
| **Schedule Expression Builder** | Builder | Build cron expressions visually with plain-English description |
| **ArgoCD App Generator** | Generator | Fill in form → get complete `Application` manifest |
| **Workflow Linter** | Linter | Paste workflow YAML → get security, best-practice, and logic issues |
| **Secret Pattern Scanner** | Security | Paste workflow or script → detect hardcoded secrets and insecure patterns |
| **OIDC Auth Snippet Builder** | Generator | Choose cloud provider → get complete keyless auth steps for AWS/GCP/Azure |
| **Matrix Strategy Builder** | Builder | Enter OS + version combos → get `strategy.matrix` YAML |
| **Rollback Command Builder** | Reference | Choose deployment method → get exact rollback commands |

### Other Sections

- **⚡ Pipeline Visualizer** — Interactive visual of GitHub Actions pipeline stages with job status simulation
- **⌘ Cheatsheet** — 120+ commands across GitHub Actions CLI, ArgoCD CLI, Git, Docker, Helm — searchable, click to copy
- **✦ Quiz** — 20 scenario-based questions (expandable to 100) across GitHub Actions, ArgoCD, GitOps, Security — with explanations
- **📋 Snippet Library** — 12+ production-ready workflow and ArgoCD manifest snippets — click to copy
- **🔴 Error Encyclopedia** — 12+ real CI/CD errors with root cause, fix commands, and prevention tips

---

## 🗂 Project Structure

```
cicd.eknathalabs.com/
└── index.html          # Entire application — single file, fully self-contained
└── README.md           # This file
```

Everything lives in `index.html`:

- All HTML, CSS, and JavaScript inline
- All data (quiz questions, cheatsheet commands, error encyclopedia, snippets) embedded as JS arrays
- No external API calls
- No frameworks — vanilla HTML/CSS/JS only
- Dark mode default with light mode toggle
- Fully responsive for mobile

---

## ✦ Quiz Topic Coverage

| Topic | Questions |
|-------|-----------|
| GitHub Actions | Triggers, OIDC, permissions, matrix, job outputs, fail-fast |
| ArgoCD | Sync phases, health states, App of Apps, Image Updater, prune |
| GitOps | Push vs pull model, separate repos, Sealed Secrets, multi-env |
| Security | SLSA, cosign, pull_request_target risk, SHA pinning, GITHUB_TOKEN scope |
| Deployment | Canary, blue-green, rollback strategies |

---

## 🔴 Error Encyclopedia Coverage

| Category | Errors Covered |
|----------|---------------|
| GitHub Actions | 403 permission denied, secret not found, PR creation blocked, context deadline |
| ArgoCD | OutOfSync, Degraded, Progressing stuck, sync wave issues, secret missing |
| Docker | Dockerfile casing, ImagePullBackOff, registry auth |
| Git | LFS limit, large file rejection |

---

## 📋 Cheatsheet Coverage

| Category | Commands |
|----------|----------|
| GitHub Actions CLI (`gh`) | `gh run list`, `gh run view`, `gh run rerun`, `gh secret set`, `gh cache` |
| ArgoCD CLI | `argocd app sync`, `argocd app rollback`, `argocd app wait`, `argocd app diff` |
| Git | `git revert`, `git cherry-pick`, `git bisect`, `git tag`, `git stash` |
| Docker | `buildx`, `cosign`, `syft`, `trivy`, multi-platform builds |
| Helm | `helm lint`, `helm template`, `helm upgrade --atomic`, `helm diff` |

---

## 🔒 Privacy & Data

- **No data leaves your browser** — everything runs client-side
- **No analytics, no tracking, no cookies**
- **No login required**
- Quiz scores and progress are session-only (not persisted)

---

## 🤝 Contributing

Found an error in the encyclopedia? Want to add a quiz question or snippet?

1. Fork the repo
2. Edit `index.html` — find the relevant data array (`quizData`, `cheatData`, `errorsData`, `snippets`)
3. Add your entry following the existing format
4. Open a PR with a short description

---

## 👤 Author

**Eknatha Reddy** — Platform Engineer, 13 years IT · 7 years cloud (AWS/Azure)

- 🌐 [eknathalabs.com](https://eknathalabs.com)
- 💻 [github.com/eknathareddyp](https://github.com/eknatha)
- ☸ [kubelab.eknathalabs.com](https://kubelab.eknathalabs.com)

---

## 📄 License

MIT — free to use, fork, and build on.

---

*Built with the same philosophy as every EknathaLabs tool: if it helps one engineer get unstuck, it was worth building.*
