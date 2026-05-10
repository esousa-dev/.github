<div align="center">

<img src="https://raw.githubusercontent.com/esousa-dev/.github/b7a14104e4601d7aecba0cba7b0f5d80e41b6776/esousa_dev_org_banner.svg" alt="esousa-dev — Reliable, production-grade software and modular systems" width="100%" />

<br /><br />

<p>
  <strong>Production-grade software. Modular by design. Open for the community.</strong>
</p>

<p>
  An engineering organization maintained by&nbsp;
  <a href="https://github.com/ESousa97"><strong>Enoque Sousa</strong></a>
  &nbsp;&mdash;&nbsp;
  IT Operations Lead &middot; Full-Stack Engineer &middot; Open-Source Author<br/>
  São Paulo, Brazil &middot; Building in public since 2022
</p>

<br/>

<a href="https://github.com/ESousa97">
  <img src="https://img.shields.io/badge/Maintained%20by-ESousa97-D07A46?style=flat-round&logo=github&logoColor=white" alt="Maintained by ESousa97" />
</a>
&nbsp;
<a href="https://www.linkedin.com/in/enoque-sousa-bb89aa168/">
  <img src="https://img.shields.io/badge/LinkedIn-Enoque%20Sousa-0A66C2?style=flat-round&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="https://enoquesousa.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-enoquesousa.vercel.app-111111?style=flat-round&logo=vercel&logoColor=white" alt="Portfolio" />
</a>

</div>

---

## About This Organization

**esousa-dev** is the production namespace for software authored by [Enoque Sousa](https://github.com/ESousa97) that is actively deployed, publicly accessible, and maintained for community use and contribution.

Every project in this organization satisfies the following criteria before being published here:

| Criterion | Requirement |
|---|---|
| Deployment | Live service with a verifiable production URL |
| Licensing | MIT — free to use, fork, and self-host |
| Documentation | README, CONTRIBUTING, CODE\_OF\_CONDUCT, SECURITY, LICENSE |
| Quality Gate | CI/CD via GitHub Actions, linting, type-checking, and `npm audit` |
| Dependency hygiene | Dependabot with grouped weekly updates |

Personal experiments, archived utilities, and learning repositories remain at [@ESousa97](https://github.com/ESousa97). This organization is reserved exclusively for what is running in production and ready for community consumption.

---

<div align="center">
  
## Production Projects

</div>

### engineering-overview-pro

> Free, public SVG card service for GitHub profiles

A read-only Fastify API (TypeScript + Node.js) that renders dynamic, embeddable SVG cards from GitHub's GraphQL API. No account, no installation — a single URL embedded in any `README.md` is all it takes.

<div align="center">

<a href="https://esousa97.com"><img src="https://img.shields.io/badge/Live%20Service-esousa97.com-1a9e6e?style=flat-round&logo=fastify&logoColor=white" alt="Live at esousa97.com" /></a>
<a href="https://github.com/esousa-dev/engineering-overview-pro"><img src="https://img.shields.io/badge/Source%20Code-GitHub-24292f?style=flat-round&logo=github&logoColor=white" alt="Source on GitHub" /></a>
<a href="https://github.com/esousa-dev/engineering-overview-pro/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-D07A46?style=flat-round" alt="MIT License" /></a>
<img src="https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-round&logo=typescript&logoColor=white" alt="TypeScript 5.8" />
<img src="https://img.shields.io/badge/Fastify-5-000000?style=flat-round&logo=fastify&logoColor=white" alt="Fastify 5" />
<img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-round&logo=node.js&logoColor=white" alt="Node.js 22" />
<img src="https://img.shields.io/badge/Vitest-tested-6E9F18?style=flat-round&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://github.com/esousa-dev/engineering-overview-pro/actions/workflows/ci.yml/badge.svg?branch=main&style=flat-round" alt="CI status" />

<br/>

</div>

**Quickstart — embed in one line:**

```md
![Stats](https://esousa97.com/api/stats?username=YOUR_LOGIN)
![Top Languages](https://esousa97.com/api/top-langs?username=YOUR_LOGIN&layout=donut)
![Streak](https://esousa97.com/api/streak?username=YOUR_LOGIN)
![Activity](https://esousa97.com/api/activity?username=YOUR_LOGIN)

```

**Available endpoints:**

| Endpoint | What it renders |
| --- | --- |
| `/api/stats` | Commits, PRs, issues, stars, and contribution rank |
| `/api/top-langs` | Language breakdown — layouts: `normal`, `compact`, `donut`, `pie` |
| `/api/streak` | Contribution streak — modes: `daily`, `weekly` |
| `/api/activity` | Activity heatmap |
| `/api/pin` | Pinned repository card grid |
| `/api/devops` | CI/CD, CodeFactor, and security signals |
| `/api/coding-stats` | Coding activity derived from public GitHub events |
| `/health` | Live JSON health snapshot (uptime, cache, rate-limit headroom) |

**Key characteristics:**

* Rate-limited to 60 requests/min per IP; CDN cache hints of 4 hours by default
* Themes: `dracula-black`, `pro-dark`; full color override via query params
* Locale support: `en`, `pt-br`, `es`
* Self-hostable on any Node.js 22+ process behind a reverse proxy
* Security: no default usernames, `TRUST_PROXY` guard, Dependabot, weekly `npm audit` in CI

---
<div align="center">
  
## Engineering Standards

</div>

All repositories under **esousa-dev** are held to the same baseline before any code reaches this organization:

```
Architecture    Modular, stateless, 12-Factor App compliant, container-ready
Security        No hardcoded secrets · sanitized inputs · npm audit passing
Quality         ESLint · Prettier · TypeScript strict · CodeFactor grade
Testing         Unit tests with coverage reporting via Vitest
CI/CD           GitHub Actions on every push and pull request to main
Dependencies    Dependabot with grouped weekly updates
Documentation   README · CONTRIBUTING · CODE_OF_CONDUCT · SECURITY · LICENSE

```

---
<div align="center">
  
## Organization Activity

</br>
  
[![Stats](https://esousa97.com/api/stats?username=ESousa97)](https://github.com/ESousa97)

[![Top Languages](https://esousa97.com/api/top-langs?username=ESousa97&layout=donut)](https://github.com/ESousa97)
 
</div>

---

<div align="center">

## Contributing

</div>

All repositories under **esousa-dev** accept community contributions. The general workflow is:

1. Read the project's `CONTRIBUTING.md` before opening any PR
2. Verify `CODE_OF_CONDUCT.md` to understand the expected standards
3. Search existing issues to avoid duplicates
4. For non-trivial changes, open an issue first to align on scope and approach

Security vulnerabilities must be disclosed through each project's `SECURITY.md`. Never report vulnerabilities in public issues.

---

<div align="center">

## Contact


| Channel | Address |
| --- | --- |
| GitHub (personal) | [@ESousa97](https://github.com/ESousa97) |
| LinkedIn | [enoque-sousa-bb89aa168](https://www.linkedin.com/in/enoque-sousa-bb89aa168/) |
| Portfolio | [enoquesousa.vercel.app](https://enoquesousa.vercel.app) |
| Email | [sousa3086@outlook.com](mailto:sousa3086@outlook.com) |

</div>

---
