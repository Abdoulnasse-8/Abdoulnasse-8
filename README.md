<h1 align="center">Abdoul Nasser HAMMA TINNI</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=B0842B&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=50&lines=%F0%9F%9A%80+%C3%89l%C3%A8ve-Ing%C3%A9nieur+G%C3%A9nie+Informatique+%E2%80%94+ENSA+Khouribga;Build+%E2%86%92+Deploy+%E2%86%92+Scale+%E2%80%94+Self-Hosted+PaaS" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/Abdoulnasse-8">
    <img src="https://img.shields.io/badge/ GitHub-Abdoulnasse--8-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/ LinkedIn-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:criminasser@gmail.com">
    <img src="https://img.shields.io/badge/ Gmail-criminasser@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/Abdoulnasse-8/mini-heroku">
    <img src="https://img.shields.io/badge/ Live-68.221.16.224:8000-00D26A?style=for-the-badge&logo=docker&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Abdoulnasse-8&color=B0842B&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

<br>

---

## 🧬 Qui suis-je ?

<table>
<tr>
<td width="180" align="center">
  <img src="https://avatars.githubusercontent.com/u/175497164?v=4" width="120" style="border-radius:50%; border: 3px solid #B0842B;" />
  <br><br>
  <b style="color:#B0842B;">Abdoul Nasser</b>
  <br>
  <sub>HAMMA TINNI</sub>
  <br><br>
  <img src="https://img.shields.io/badge/📍_ENSA_Khouribga-1B2A4A?style=flat-square&labelColor=1B2A4A" />
  <br>
  <img src="https://img.shields.io/badge/🎓_1337_Coding_School-1B2A4A?style=flat-square&labelColor=1B2A4A" />
</td>
<td valign="middle" style="padding-left: 30px;">

Élève-ingénieur en **5e année Génie Informatique** (option SCIL) à l'ENSA Khouribga.
Élève à l'**École 1337 Coding School** — Khouribga (réseau 42).

Je construis des **plateformes réelles**, pas des maquettes.
De la VM Azure au premier commit, chaque projet est **déployé, testé et documenté**.

> *"Learning by doing. Peer-to-peer. Zero instruction."*

</td>
</tr>
</table>

<br>

---

## ⚡ Projets Phares

<table>
<tr>
<td width="50%" valign="top" style="border: 2px solid #1E2A4A; border-radius: 12px; padding: 20px;">

### ⚡ [Mini-Heroku](https://github.com/Abdoulnasse-8/mini-heroku)
<p style="color: #8B98C7; font-size: 14px;">
Plateforme PaaS self-hosted — <code>git push → HTTPS en &lt; 2 min</code>
</p>

<p>
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-0.100+-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-24+-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Caddy-2.11-FF6833?style=for-the-badge&logoColor=white" />
</p>

```
VM Azure 13.00$ → 1 seul conteneur FastAPI
git push → clone → build → push :5000 → run → Caddy → HTTPS
```

| ✅ Fonctionnalité | Statut |
|:---|:---|
| Git push deploy (SSH) | ✅ |
| Docker build automatique | ✅ |
| HTTPS Let's Encrypt | ✅ |
| Variables d'environnement (Fernet AES-128) | ✅ |
| Logs temps réel (SSE) | ✅ |
| Métriques CPU/RAM (Chart.js) | ✅ |
| Scaling horizontal + load balancing | ✅ |
| Rollback instantané | ✅ |
| Add-ons PostgreSQL / Redis | ✅ |
| Interface Web + CLI (24 commandes) | ✅ |
| **29 tests** — 0 failed | ✅ |

</td>
<td width="50%" valign="top" style="border: 2px solid #1E2A4A; border-radius: 12px; padding: 20px;">

### 🏥 [Cabinet Médical](https://github.com/Abdoulnasse-8/CabinetMedical)
<p style="color: #8B98C7; font-size: 14px;">
Application 3 tiers — déployée sur Mini-Heroku
</p>

<p>
  <img src="https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-3+-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-14-000000?style=for-the-badge&logo=next.js&logoColor=white" />
</p>

```
3 composants → 1 repo → 3 conteneurs Docker
cabinetmedical → Next.js (HTTPS)
cabinet-api   → Spring Boot (HTTPS)
cabinet-db    → PostgreSQL (add-on)
```

| ✅ Composant | Stack | URL |
|:---|:---|:---|
| Frontend | Next.js 14 | `cabinetmedical.68.221.16.224.sslip.io` |
| Backend API | Spring Boot 3 | `cabinet-api.68.221.16.224.sslip.io` |
| Base de données | PostgreSQL 16 | Auto-provisioned via add-on |

<p style="color: #B0842B; font-size: 13px;">
🔐 Login : admin / password
</p>

</td>
</tr>
</table>

<br>

---

## 🏗️ Architecture

```
                        ┌─────────────────────────────────────────┐
                        │         MINI-HEROKU — 1 VM Azure        │
                        │              Ubuntu 24.04               │
                        └─────────────────────────────────────────┘

  👨‍💻 Développeur                ┌──────────────┐
  ──────────────                │   FastAPI    │
        │                       │    :8000     │
        │  git push / CLI / UI  │   (Control   │
        ├──────────────────────►│    Plane)    │
        │                       └──────┬───────┘
        │                              │
        │                    ┌─────────┴─────────┐
        │                    │                   │
        │              ┌─────▼─────┐       ┌─────▼─────┐
        │              │  Builder  │       │   Runner  │
        │              │  (clone   │       │  (run     │
        │              │  build    │       │  CPU/RAM  │
        │              │  push)    │       │  health)  │
        │              └─────┬─────┘       └─────┬─────┘
        │                    │                   │
        │              ┌─────▼─────┐       ┌─────▼─────┐
        │              │ Registry  │       │   Caddy   │
        │              │   :5000   │       │  :80/443  │
        │              └───────────┘       └─────┬─────┘
        │                                        │
        │                              ┌─────────▼─────────┐
        │                              │  HTTPS automatique │
        │                              │  <app>.IP.sslip.io │
        │                              │  Let's Encrypt     │
        │                              └───────────────────┘
        │
  📂 SQLite + Fernet AES-128 (variables chiffrées)
```

<br>

---

## 🛠️ Stack Technique

<table>
<tr>
<td width="33%" align="center">
  <b style="color:#B0842B;">☁️ Infra & DevOps</b>
  <br><br>
  <img src="https://img.shields.io/badge/Linux-Ubuntu_24.04-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Docker-24+-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Caddy-2.11-FF6833?style=flat-square" />
  <br>
  <img src="https://img.shields.io/badge/Azure_VM-13.00$_0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/systemd-service-333333?style=flat-square" />
</td>
<td width="33%" align="center">
  <b style="color:#B0842B;">⚙️ Backend & Data</b>
  <br><br>
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/FastAPI-0.100+-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Fernet-AES--128-9B59B6?style=flat-square" />
  <br>
  <img src="https://img.shields.io/badge/Click-CLI-000000?style=flat-square" />
</td>
<td width="33%" align="center">
  <b style="color:#B0842B;">🎨 Frontend & Monitoring</b>
  <br><br>
  <img src="https://img.shields.io/badge/Jinja2-Templates-2ECC71?style=flat-square" />
  <br>
  <img src="https://img.shields.io/badge/HTMX-333333?style=flat-square&logo=htmx&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/Chart.js-Metrics-FF6384?style=flat-square&logo=chart.js&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/SSE-Logs-FF9800?style=flat-square" />
  <br>
  <img src="https://img.shields.io/badge/Swagger-API_DOCS-6DB33F?style=flat-square&logo=swagger&logoColor=white" />
</td>
</tr>
</table>

<br>

---

## 📊 Statistiques

<table>
<tr>
<td width="50%" align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Abdoulnasse-8&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=B0842B&icon_color=58A6FF&count_private=true)

</td>
<td width="50%" align="center">

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Abdoulnasse-8&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=B0842B&langs_count=8)

</td>
</tr>
</table>

<br>

---

## 🏅 Certifications

<table>
<tr>
<td align="center" width="33%">
  <img src="https://img.shields.io/badge/Oracle_Cloud-OCI_Foundations-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
  <br><br>
  <b>1Z0-1085-26</b>
  <br>
  <sub>OCI Foundations Associate</sub>
</td>
<td align="center" width="33%">
  <img src="https://img.shields.io/badge/Red_Hat-RH124-EE0000?style=for-the-badge&logo=redhat&logoColor=white" />
  <br><br>
  <b>System Administration I</b>
  <br>
  <sub>Red Hat Enterprise Linux</sub>
</td>
<td align="center" width="33%">
  <img src="https://img.shields.io/badge/1337-Missing_Layer-1B2A4A?style=for-the-badge&logo=1337&logoColor=white" />
  <br><br>
  <b>Docker & Kubernetes</b>
  <br>
  <sub>1337 Coding School</sub>
</td>
</tr>
</table>

<br>

---

## 🎯 Roadmap

```
 ✅ 2025-2026   PFA Mini-Heroku — PaaS self-hosted complet
 ✅ 2025        Oracle OCI Foundations Associate
 ✅ 2025        Red Hat RH124
 ✅ 2025        1337 Missing Layer (Docker/K8s)
 🔄 2026        Certification AWS SAA ou Azure AZ-104
 🔄 2026        Kubernetes CKA (Certified Kubernetes Admin)
 🔄 2026        Stage ingénieur — DevOps / Cloud / SRE
```

<br>

---

## 📂 Tous les Repositories

| Projet | Description | Stack | Lien |
|:---|:---|:---|:---|
| ⚡ **Mini-Heroku** | Plateforme PaaS self-hosted | Python, FastAPI, Docker, Caddy | [→](https://github.com/Abdoulnasse-8/mini-heroku) |
| 🏥 **CabinetMedical** | Application médicale 3 tiers | TypeScript, Spring Boot, PostgreSQL | [→](https://github.com/Abdoulnasse-8/CabinetMedical) |
| 🏙️ **Urban-Report** | Application de reporting urbain | CSS | [→](https://github.com/Abdoulnasse-8/Urban-Report) |
| 🧠 **SInteliggent** | Système intelligent | JavaScript | [→](https://github.com/Abdoulnasse-8/SInteliggent) |
| 📚 **LIBFT** | Bibliothèque C — 1337 | C | [→](https://github.com/Abdoulnasse-8/LIBFT) |
| 🔄 **push_swap_42** | Algorithme de tri — 42 | C | [→](https://github.com/Abdoulnasse-8/push_swap_42) |
| 🗄️ **TP7_API_TEST** | API REST + MongoDB | JavaScript | [→](https://github.com/Abdoulnasse-8/TP7_API_TEST_WITH_MONGODB) |

<br>

---

<div align="center">

### *"De la conception à la mise en production, en autonomie — c'est ça, l'esprit 1337."*

<br>

![Waving Hand](https://raw.githubusercontent.com/Abdoulnasse-8/Abdoulnasse-8/main/wave.gif)

<br>

**Built with ❤️ by Abdoul Nasser HAMMA TINNI**

*ENSA Khouribga · 1337 Coding School · 2025-2026*

</div>
