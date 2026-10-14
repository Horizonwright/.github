<p align="center">
  <img src="https://raw.githubusercontent.com/Horizonwright/.github/main/brand/banner-1280x400.png" alt="Horizonwright — build toward the horizon" width="100%">
</p>

<p align="center">
  <b>We build products, the platforms under them, and the agents that run them.</b><br>
  Small team · production-first · everything automated, tested and observable.
</p>

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-0B1016?style=flat-square&logo=typescript&logoColor=22D3C5">
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-0B1016?style=flat-square&logo=nestjs&logoColor=22D3C5">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0B1016?style=flat-square&logo=postgresql&logoColor=22D3C5">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-0B1016?style=flat-square&logo=redis&logoColor=22D3C5">
  <img alt="Nx" src="https://img.shields.io/badge/Nx-0B1016?style=flat-square&logo=nx&logoColor=22D3C5">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-0B1016?style=flat-square&logo=githubactions&logoColor=22D3C5">
  <img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-0B1016?style=flat-square&logo=cloudflareworkers&logoColor=22D3C5">
</p>

---

## ◆ What we do

- **Products** — consumer apps for iOS and Android, built mobile-first.
- **Platforms** — the APIs, data and realtime systems underneath them.
- **Agents** — automation that runs the work around the code: tracking, CI, deploys, uptime.

## ◆ How we build

- **Issue first.** Every change starts as an issue; every PR closes one.
- **Green or it doesn't ship.** Lint, typecheck, unit tests, migration dry-runs and smoke tests on every PR; end-to-end user-journey tests run nightly.
- **Deploys are boring.** Migrate → deploy → verify, in that order, from one pipeline.
- **Everything reports in.** Issues, PRs, CI, deploys, errors and uptime land in one place, automatically.

```mermaid
flowchart LR
  I[Issue] --> P[Pull request<br/>Closes #issue]
  P --> C{CI}
  C -- green --> M[Merge]
  C -- red --> P
  M --> D[Migrate → Deploy → Verify]
  I -.-> A((Atlas))
  P -.-> A
  C -.-> A
  D -.-> A
  A --> X[Discord<br/>one thread per issue]
```

## ◆ Working with us

Contribution guide, issue and PR templates and our code of conduct live in [this repository](https://github.com/Horizonwright/.github).
Found a security problem? Please report it privately — see [SECURITY.md](https://github.com/Horizonwright/.github/blob/main/SECURITY.md).

<p align="center"><sub>Horizonwright · est. 2026</sub></p>
