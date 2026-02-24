# Noctumbra-Mail

<p align="center">
  <img src="./assets/branding/logo.svg" alt="Noctumbra-Mail logo" width="88" />
</p>

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![License](https://img.shields.io/github/license/smouj/Noctumbra-Mail)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Noctumbra-Mail)
![CI](https://img.shields.io/github/actions/workflow/status/smouj/Noctumbra-Mail/ci.yml?branch=main)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/smouj013_dev)

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

**Zero-touch email orchestration with policy-safe automation.**

## Vision
Classifies, drafts, and automates repetitive email actions through local logic.

## What problem it solves
Inbox overload reduces response quality and speed.

## Core superpower
- ⚡ **Autonomous triage and draft pipelines with controlled execution**

## Key use cases
- ✅ Inbox triage
- ✅ Draft generation
- ✅ Unsubscribe automation
- ✅ Email action routing


## API surface
`POST /send`, `POST /classify`, `POST /draft`, `POST /unsubscribe`, `GET /health`

## Technical stack
- **Core stack:** FastAPI + IMAP/SMTP adapters + local NLP
- **Runtime:** local-first, self-hosted friendly
- **Infra:** Docker Compose + Caddy + Redis/Chroma/Ollama compatibility

## Current status (Feb 2026)
- ✅ Public scaffold available
- ✅ Bilingual README (EN default + ES)
- ✅ CI + release baseline configured
- 🚧 Feature hardening in progress

## Quick start
```bash
git clone https://github.com/smouj/Noctumbra-Mail.git
cd Noctumbra-Mail
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.noctumbra_mail.cli --help
```

## Documentation
- [Implementation Guide](./docs/IMPLEMENTATION.md)
- [Architecture](./docs/ARCHITECTURE.md)
- [Runbook](./docs/RUNBOOK.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [Release Process](./docs/RELEASE.md)
- [Changelog](./CHANGELOG.md)

## Contributing
Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md).

## License
MIT © 2026 smouj

---

### Other skills
Explore the full ecosystem here: **[smouj/smouj](https://github.com/smouj/smouj)**

**Signature:** [@Smouj013](https://x.com/smouj013)
