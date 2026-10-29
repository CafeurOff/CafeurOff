<h1 align="center">Lorenzo Duthilleul</h1>

<p align="center">
  <b>Freelance full-stack developer · founder of <a href="https://www.omexis.fr">Omexis</a></b><br>
  I build business software end to end: interface, API, database, servers, and the on-call afterwards.
</p>

<p align="center">
  <a href="https://www.omexis.fr">omexis.fr</a> ·
  <a href="https://invoice.omexis.fr">Omexis Invoice</a> ·
  <a href="https://status.omexis.fr">Status</a> ·
  <a href="https://www.linkedin.com/in/lduthill">LinkedIn</a> ·
  <a href="https://linktree.omexis.fr">All links</a> ·
  <a href="mailto:lduthill@icloud.com">Email</a>
</p>

<p align="center"><sub>Perpignan, France · École 42 · Shipping to production since 2023</sub></p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=CafeurOff&label=profile%20views&color=663BE0&style=flat-square" alt="Profile views">
</p>

---

### Right now

- Running **Omexis Invoice** in production, solo: features, support, deploys, incidents.
- Building **matcher42**, a swipe-style job board between École 42 students and companies.
- Keeping one Debian VPS healthy for several products, and turning what it taught me into reusable tooling.

---

### Things I've built

#### [Omexis Invoice](https://invoice.omexis.fr) &nbsp;<sub>SaaS · in production · private repo</sub>

French B2B invoicing for freelancers and small businesses: quotes, invoices, credit notes, online payment, automatic reminders, accounting export, time tracking, supplier OCR.

- **Factur-X (EN 16931)** generated natively, with schematron validation before anything leaves the app.
- **MCP server** so you can run your billing from Claude: OAuth 2.1, Streamable HTTP, a thin client over the same REST API the app uses.
- Multi-tenant Django with one company UUID as the isolation boundary, Celery for PDFs, reminders and recurring invoices, Stripe Connect for payments.
- Public [status page](https://status.omexis.fr) probed every 5 minutes by a Cloudflare Worker, independent of the VPS it watches.

`Django 5.2` `DRF` `Celery` `Redis` `PostgreSQL` `React 19` `TanStack Query` `Tailwind` `Stripe` `MCP`

#### [Malo Creations](https://malocreations.fr) &nbsp;<sub>client SaaS · in production · private repo</sub>

Business software for a building project manager: projects and clients, automatic quotes and invoices, **CERFA forms filled automatically**, floor-area calculations, contracts, documents, and a dedicated client portal. Public site, admin dashboard and portal in one codebase.

`Django 5.2` `DRF` `Channels` `PostgreSQL` `React 19` `Tailwind` `Docker`

#### matcher42 &nbsp;<sub>in progress · private repo</sub>

Students sign in with their 42 Intra account (OAuth2), their profile is imported, then they swipe on internships and jobs. Companies get their own space, staff get a moderation panel, matches open a real-time chat.

`Django` `Channels` `Redis` `PostgreSQL` `React 19` `Vite`

#### vps-infra &nbsp;<sub>ops tooling · private repo</sub>

The production patterns I hardened by hand (systemd limits, nginx rate limiting, a deploy script with automatic rollback, backups with real restore tests, Prometheus alerts) turned into templates and a bootstrap script. A new project answers a questionnaire instead of re-deriving all of it. Dry-run by default, typed confirmation for anything destructive.

`Bash` `systemd` `nginx` `GitHub Actions` `Prometheus`

#### [Beggin RolePlay](https://beggin.fr) &nbsp;<sub>gaming community · team project</sub>

Main contributor to the website of a Garry's Mod roleplay community (1,000+ commits): shop with Stripe, accounts, purchase history, i18n. Also contributed to the Express API that serves the site, the Discord bots and the game server.

`React` `Tailwind` `TanStack Query` `Stripe` `Express` `MySQL`

---

### From École 42

Where I learned to read man pages before Stack Overflow.

| Project | What it is |
|---|---|
| [Minishell](https://github.com/CafeurOff/Minishell) | A small shell in C: pipes, redirections, signals, error handling |
| [Cub3D](https://github.com/CafeurOff/Cub3D) | A raycasting engine in C with miniLibX, Wolfenstein 3D style |
| [ft_irc](https://github.com/CafeurOff/ft_irc) | An IRC server in C++ following RFC 1459: channels, private messages, commands |
| [Philosophers](https://github.com/CafeurOff/Philosopher) | The dining philosophers with threads and mutexes |
| [ft_transcendence](https://github.com/CafeurOff/ft_transcendence) | Real-time multiplayer Pong website with OAuth2 and chat |
| [Inception](https://github.com/CafeurOff/Inception) | A small Docker Compose infrastructure built from scratch |

---

### What I work with

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,js,react,vite,tailwind,postgres,redis,celery&perline=9" alt="Python, Django, JavaScript, React, Vite, Tailwind, PostgreSQL, Redis, Celery"><br>
  <img src="https://skillicons.dev/icons?i=linux,nginx,githubactions,cloudflare,sentry,prometheus,grafana,docker,bash&perline=9" alt="Linux, nginx, GitHub Actions, Cloudflare, Sentry, Prometheus, Grafana, Docker, Bash"><br>
  <img src="https://skillicons.dev/icons?i=c,cpp,nodejs,express,mysql,stripe&perline=9" alt="C, C++, Node.js, Express, MySQL, Stripe">
</p>

**Daily** &nbsp; Python · Django · DRF · JavaScript · React · Vite · TanStack Query · Tailwind · PostgreSQL · Redis · Celery

**Production** &nbsp; Debian · nginx · systemd · GitHub Actions · Cloudflare Pages & Workers · Sentry · Prometheus · Grafana

**Also** &nbsp; C · C++ · Node.js / Express · MySQL · Docker · Stripe · MCP · Bash

---

### Activity

<sub>Most commits land in private repos; they are counted here.</sub>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=CafeurOff&hide_border=true&background=00000000&ring=967AFA&fire=967AFA&currStreakLabel=967AFA&sideLabels=E6E6EA&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=A1A1AA&stroke=3F3F46&locale=en">
    <img src="https://streak-stats.demolab.com?user=CafeurOff&hide_border=true&background=00000000&ring=663BE0&fire=663BE0&currStreakLabel=663BE0&sideLabels=27272A&currStreakNum=18181B&sideNums=18181B&dates=71717A&stroke=E4E4E7&locale=en" alt="GitHub contribution streak">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CafeurOff/CafeurOff/output/github-snake-dark.svg">
    <img src="https://raw.githubusercontent.com/CafeurOff/CafeurOff/output/github-snake.svg" alt="Contribution graph eaten by a snake">
  </picture>
</p>

---

### How I work

- **One person from the first call to production.** Nothing gets lost between a salesperson and a developer.
- **Compliance from day one.** GDPR, legal mentions, e-invoicing: designed in, not patched on.
- **Boring, observable infrastructure.** Health checks, rollbacks and backups I have actually restored.
- **Interfaces people want to open.** Plain words, one action colour, no dashboard template.

---

<p align="center">
  <sub>Most of my work lives in private repos for clients. Happy to walk you through it:
  <a href="mailto:lduthill@icloud.com">lduthill@icloud.com</a></sub>
</p>
