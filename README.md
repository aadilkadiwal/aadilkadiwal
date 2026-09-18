<div align="center">

# Aadil Kadiwal

### Senior Software Engineer · Django · Vue 3 · Cloud · Mumbai

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=2F81F7&center=true&vCenter=true&width=620&lines=Five+years+on+Python+and+Django;Django+%7C+DRF+%7C+Celery+%7C+PostgreSQL;Vue+3+%7C+Nuxt+%7C+TypeScript;AWS%2C+Azure+and+GCP+%E2%80%94+and+the+pipeline+too)](https://github.com/aadilkadiwal)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aadil-kadiwal)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aadilkadiwal4277@gmail.com)
![Location](https://img.shields.io/badge/Mumbai,%20India-34A853?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## About

- Senior Software Engineer at [@pixeldust-in](https://github.com/pixeldust-in). Lead engineer on two fintech products, and I own the release pipeline on both.
- Five years on **Python** and **Django**, and usually the **Vue 3** front end and the deployment as well.
- Owned deployment end to end on both codebases. **Docker** images pinned to fixed versions and run as a non-root user, **GitHub Actions** for the release, Nginx with automatic HTTPS certificates, and secrets in Doppler.
- Work across **AWS, Azure and GCP**, including an internal platform that brings all three bills into one cost model.
- I mentor through code review rather than rewriting branches. One intern went from first commit to owning a platform feature in six months.

---

## Selected Work

**Multi-Cloud Cost Platform**

Brings AWS, Azure and GCP bills into one cost model, so teams see and forecast total spend in one **Vue 3** dashboard instead of three provider consoles. Daily imports and forecasts run on scheduled **Celery** jobs.

**Investor Relations Platform**

Lead engineer on a platform for an advisory firm serving listed companies. Target lists, roadshows, research coverage, and documents on **S3** where each user sees only what their role allows. Sole author of the invitation and onboarding flow.

**Proxy Voting Platform**

Built the custodian module, where institutions vote on behalf of their investors. Every investor, scheme, holdings file and e-voting upload needs a second person's approval across **six roles**, and the system checks who held the shares on the record date.

**Partner Platform, Fortune 50 FMCG**

Grew it from **20K to 160K** monthly users. The site was never the bottleneck. Agencies were waiting on emailed reports. Gave each agency its own trackable links, then a dashboard where they pulled their own numbers and Excel exports without asking anyone.

**Database upgrades**

Upgraded **10 PostgreSQL** databases from v11 to v17, about **9 million** records across 30+ tables. Ran the upgrades one at a time, each with its own rollback plan, and finished with no data loss.

**Performance**

Cut API response times by about **40%** with Redis caching, targeted PostgreSQL indexes and read-replica queries.

---

## Tech

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-A30000?style=flat-square&logo=django&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend**

![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=pinia&logoColor=black)
![Ant Design Vue](https://img.shields.io/badge/Ant%20Design%20Vue-0170FE?style=flat-square&logo=antdesign&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Cloud**

![AWS](https://img.shields.io/badge/AWS%20%C2%B7%20EC2,%20S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure%20%C2%B7%20App%20Service,%20Pipelines-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP%20%C2%B7%20BigQuery,%20Cloud%20Billing-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**DevOps & Quality**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Doppler](https://img.shields.io/badge/Doppler-3B3B98?style=flat-square&logo=doppler&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Snyk](https://img.shields.io/badge/Snyk-4C4A73?style=flat-square&logo=snyk&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black)

---

## Projects

**[Equity Research Journal](https://equity-research-journal.pages.dev)** — *Astro · Cloudflare Pages Functions · Python · GitHub Actions*

Brokerage apps only give a few hundred characters for notes, which is not enough room to write down *why*. Every company I read gets a file here instead: the view in plain English, a multibagger score out of 100, and an AI-written report on the earnings call. Read it again next quarter and the old call stays put, so a change of mind is part of the record. No database and no server. A scheduled **GitHub Actions** job recalculates the price trends after market close, committing only what changed.

---

## Certification

**Claude Certified Architect — Foundations**, Anthropic. September 2026.

---

## GitHub

<div align="center">

![Aadil's GitHub stats](./profile/stats.svg)
![GitHub Streak](./profile/streak.svg)

</div>

> These cards are built once a day by [a GitHub Actions workflow](.github/workflows/profile-cards.yml) in this
> repository and committed as SVG files, so they load from GitHub rather than an outside service. The workflow uses a
> personal access token, which is what lets private contributions count.

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=aadilkadiwal&style=flat-square&color=2F81F7)

*Most of my recent work is in private organisation repositories. The stats above include it.*

</div>
