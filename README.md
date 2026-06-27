# Hi 👋 I'm Michele Angrisano

## Software Engineer — Authentication & PKI

I build security software in **Python, C++ and TypeScript** that ships to production.
I care about clean design, algorithms, and systems that hold up under real load.

- 📍 Based in Napoli, Italy
- 🏢 Software Engineer at [Bit4id](https://www.bit4id.com)/[Namirial](https://www.namirial.it) — authentication & PKI
- 🗣️ Italian (native) · English (professional)
- 🌍 [LinkedIn](https://www.linkedin.com/in/michele-angrisano-2b812a1b8/) · ✉️ [michele.angrisano@gmail.com](mailto:michele.angrisano@gmail.com)

---

### 🔐 What I work on

**[Namirial SafeAccess](https://www.namirial.com/en/security/passwordless-authentication/)** — a passwordless, phishing-resistant MFA suite for enterprises, built on **FIDO2** and **PKI**, securing access to Windows workstations and web/legacy apps.

- Built core parts of the **Python backend** and **native Node/C++ modules** powering passwordless login on enterprise workstations.
- Designed and shipped **TypeScript** modules for the web/integration layer.
- Work hands-on with **PKI**, **X.509** and the **TLS/SSL** certificate lifecycle.

---

### 📦 Open source

I build and ship my own tooling — small, focused, production-grade.

**[certinspect](https://github.com/mangrisano/certinspect)** — single-purpose X.509/TLS certificate inspector. Checks expiry, chain of trust, OCSP/CRL revocation, weak crypto and hostname match. Speaks plain text, JSON, CSV, Nagios and Prometheus; batch mode with concurrency and CI-friendly exit codes.
`pip install certinspect`

[![PyPI](https://img.shields.io/pypi/v/certinspect?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/certinspect/)
[![Python](https://img.shields.io/pypi/pyversions/certinspect?style=flat-square&logo=python&logoColor=white&color=3776AB)](https://pypi.org/project/certinspect/)
[![Stars](https://img.shields.io/github/stars/mangrisano/certinspect?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/certinspect)

**[certminder](https://github.com/mangrisano/certminder)** — continuous TLS certificate monitor & alerter built on top of certinspect: scheduled checks, state memory, dedup and notifications (console / email / Slack / webhook). Currently monitoring **63 public-healthcare TLS endpoints** in production.
`pip install certminder`

[![PyPI](https://img.shields.io/pypi/v/certminder?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/certminder/)
[![Python](https://img.shields.io/pypi/pyversions/certminder?style=flat-square&logo=python&logoColor=white&color=3776AB)](https://pypi.org/project/certminder/)
[![Stars](https://img.shields.io/github/stars/mangrisano/certminder?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/certminder)


**[cvewatcher](https://github.com/mangrisano/cvewatcher)** — self-hosted FastAPI service that matches your software inventory against the NIST NVD: precise CPE lookups, automatic CPE resolution and keyword fallback, severity/time triage, background monitoring and a no-build web dashboard.
`docker pull micheleangrisano/cvewatcher`

[![Release](https://img.shields.io/github/v/release/mangrisano/cvewatcher?style=flat-square&logo=github&logoColor=white&color=3775A9)](https://github.com/mangrisano/cvewatcher/releases)
[![Python](https://img.shields.io/badge/python-3-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/mangrisano/cvewatcher/blob/main/pyproject.toml)
[![Container](https://img.shields.io/badge/ghcr.io-cvewatcher-2496ED?style=flat-square&logo=docker&logoColor=white)](https://github.com/mangrisano/cvewatcher/pkgs/container/cvewatcher)
[![Stars](https://img.shields.io/github/stars/mangrisano/cvewatcher?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/cvewatcher)

---

### 🛠️ Tech I reach for

- **Languages:** Python · C++ · TypeScript · Node.js
- **Infra & data:** Docker · Linux · PostgreSQL
- **Domain:** PKI · X.509 · TLS/SSL · FIDO2

---

### 🔭 Currently

Deep into **certificate-lifecycle automation** — OCSP/CRL revocation, TLS monitoring, and CI-friendly PKI tooling.

---

<a href="https://github.com/mangrisano">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mangrisano&show_icons=true&hide_border=true&theme=default&count_private=true" alt="Michele's GitHub stats" />
</a>
<a href="https://github.com/mangrisano">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mangrisano&layout=compact&hide_border=true&theme=default" alt="Top languages" />
</a>

---

💬 Happy to talk about **PKI, security tooling and backend systems** — feel free to reach out.
