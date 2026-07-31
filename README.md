# Hi 👋 I'm Michele Angrisano

## Software Engineer — Authentication & PKI

I build security software in **Python, C++ and TypeScript** that ships to production.
I care about clean design, algorithms, and systems that hold up under real load.

The same **PKI / TLS** expertise runs through everything I do — from **FIDO2 and
X.509** in the product I work on to the open-source tooling I build around
certificate inspection, monitoring and the TLS lifecycle.

- 📍 Based in Napoli, Italy
- 🏢 Software Engineer at [Namirial](https://www.namirial.it) since 2022 — authentication & PKI
- 🗣️ Italian (native) · English (professional)
- 🌍 [LinkedIn](https://www.linkedin.com/in/michele-angrisano-2b812a1b8/) · ✉️ [michele.angrisano@gmail.com](mailto:michele.angrisano@gmail.com)

---

### 🔐 What I work on

**[Namirial SafeAccess](https://www.namirial.com/en/security/passwordless-authentication/)** — a passwordless, phishing-resistant MFA suite for enterprises, built on **FIDO2** and **PKI**, securing access to Windows workstations and web/legacy apps.

- Built core parts of the **Python backend** and **native Node/C++ modules** powering passwordless login on enterprise workstations.
- Designed and shipped **TypeScript** modules for the web/integration layer.
- Work hands-on with **PKI**, **X.509** and the **TLS/SSL** certificate lifecycle.

Beyond the product, I build **enterprise backends in Python / FastAPI** — including **SOAP** integrations and services around **remote signing** and **Certificate Authority (CA)** infrastructure.

---

### 📦 Open source

I build and ship my own tooling — small, focused, production-grade.

**[certinspect](https://github.com/mangrisano/certinspect)** — single-purpose X.509/TLS certificate inspector. Checks expiry, chain of trust, OCSP/CRL revocation, weak crypto and hostname match. Speaks plain text, JSON, CSV, Nagios and Prometheus; batch mode with concurrency and CI-friendly exit codes.

`pip install certinspect`

[![PyPI](https://img.shields.io/pypi/v/certinspect?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/certinspect/)
[![Python](https://img.shields.io/pypi/pyversions/certinspect?style=flat-square&logo=python&logoColor=white&color=3776AB)](https://pypi.org/project/certinspect/)
[![Downloads](https://img.shields.io/pypi/dm/certinspect?style=flat-square&logo=pypi&logoColor=white&label=downloads&color=3775A9)](https://pypi.org/project/certinspect/)
[![Stars](https://img.shields.io/github/stars/mangrisano/certinspect?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/certinspect)

<img src="https://raw.githubusercontent.com/mangrisano/certinspect/main/docs/demo.gif" alt="certinspect demo" width="640">

**[certminder](https://github.com/mangrisano/certminder)** — continuous TLS certificate monitor & alerter built on top of certinspect: scheduled checks, state memory, dedup and notifications (console / email / Slack / webhook). Currently monitoring **78 public-healthcare TLS endpoints** in production.

`pip install certminder`

[![PyPI](https://img.shields.io/pypi/v/certminder?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/certminder/)
[![Python](https://img.shields.io/pypi/pyversions/certminder?style=flat-square&logo=python&logoColor=white&color=3776AB)](https://pypi.org/project/certminder/)
[![Downloads](https://img.shields.io/pypi/dm/certminder?style=flat-square&logo=pypi&logoColor=white&label=downloads&color=3775A9)](https://pypi.org/project/certminder/)
[![Stars](https://img.shields.io/github/stars/mangrisano/certminder?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/certminder)

**[cvewatcher](https://github.com/mangrisano/cvewatcher)** — self-hosted FastAPI service that matches your software inventory against the NIST NVD: precise CPE lookups, automatic CPE resolution and keyword fallback, severity/time triage, background monitoring and a no-build web dashboard.

`docker pull micheleangrisano/cvewatcher`

[![Release](https://img.shields.io/github/v/release/mangrisano/cvewatcher?style=flat-square&logo=github&logoColor=white&color=3775A9)](https://github.com/mangrisano/cvewatcher/releases)
[![Python](https://img.shields.io/badge/python-3-3776AB?style=flat-square&logo=python&logoColor=white)](https://github.com/mangrisano/cvewatcher/blob/main/pyproject.toml)
[![Docker Pulls](https://img.shields.io/docker/pulls/micheleangrisano/cvewatcher?style=flat-square&logo=docker&logoColor=white&label=pulls&color=2496ED)](https://hub.docker.com/r/micheleangrisano/cvewatcher)
[![Image Size](https://img.shields.io/docker/image-size/micheleangrisano/cvewatcher/latest?style=flat-square&logo=docker&logoColor=white&color=2496ED)](https://hub.docker.com/r/micheleangrisano/cvewatcher)
[![Stars](https://img.shields.io/github/stars/mangrisano/cvewatcher?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/cvewatcher)

**[jpick](https://github.com/mangrisano/jpick)** — tiny `jq`-like JSON tool written in C++20: a hand-written lexer and recursive-descent parser over a `std::variant` data model. Query with object keys, array indices, iteration (`[]`) and the pipe operator (`|`); build strings with interpolation (`"\(.name)"`); compact, pretty or raw (`-r`) output; reads from stdin or a file.

`brew install mangrisano/jpick/jpick`

[![Release](https://img.shields.io/github/v/release/mangrisano/jpick?style=flat-square&logo=github&logoColor=white&color=3775A9)](https://github.com/mangrisano/jpick/releases)
[![C++](https://img.shields.io/badge/C%2B%2B-20-00599C?style=flat-square&logo=cplusplus&logoColor=white)](https://github.com/mangrisano/jpick/blob/main/CMakeLists.txt)
[![Downloads](https://img.shields.io/github/downloads/mangrisano/jpick/total?style=flat-square&logo=github&logoColor=white&label=downloads&color=181717)](https://github.com/mangrisano/jpick/releases)
[![Stars](https://img.shields.io/github/stars/mangrisano/jpick?style=flat-square&logo=github&logoColor=white&color=181717)](https://github.com/mangrisano/jpick)

<img src="https://raw.githubusercontent.com/mangrisano/jpick/main/docs/demo.gif" alt="jpick demo" width="640">

---

### 🛠️ Tech I reach for

- **Languages:** Python · C++ · TypeScript · Node.js
- **Backend:** FastAPI · SOAP · REST
- **Infra & data:** Docker · Linux · PostgreSQL
- **Domain:** PKI · X.509 · TLS/SSL · FIDO2 · remote signing · CA

---

### 🔭 Currently

On the open-source side, I keep building and maintaining my own **certificate-lifecycle tooling** — TLS/PKI inspection, monitoring and revocation — plus small focused utilities that scratch my own itch.

---

### ❤️ Support my work

If my open-source tooling saves you time, you can support its continued
development through **[GitHub Sponsors](https://github.com/sponsors/mangrisano)**.

[![Sponsor](https://img.shields.io/github/sponsors/mangrisano?style=flat-square&logo=githubsponsors&logoColor=white&label=Sponsor&color=EA4AAA)](https://github.com/sponsors/mangrisano)
[![Follow](https://img.shields.io/github/followers/mangrisano?style=flat-square&logo=github&logoColor=white&label=Follow&color=181717)](https://github.com/mangrisano)

---

Happy to talk about **PKI, security tooling and backend systems** — reach out on
[LinkedIn](https://www.linkedin.com/in/michele-angrisano-2b812a1b8/) or by [email](mailto:michele.angrisano@gmail.com).
