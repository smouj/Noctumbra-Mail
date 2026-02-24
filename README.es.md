# Noctumbra-Mail

<p align="center">
  <img src="./assets/branding/logo.svg" alt="Logo de Noctumbra-Mail" width="88" />
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

## Visión
Classifies, drafts, and automates repetitive email actions through local logic.

## Problema que resuelve
Inbox overload reduces response quality and speed.

## Superpoder principal
- ⚡ **Autonomous triage and draft pipelines with controlled execution**

## Casos de uso clave
- ✅ Inbox triage
- ✅ Draft generation
- ✅ Unsubscribe automation
- ✅ Email action routing


## Superficie API
`POST /send`, `POST /classify`, `POST /draft`, `POST /unsubscribe`, `GET /health`

## Stack técnico
- **Stack base:** FastAPI + IMAP/SMTP adapters + local NLP
- **Ejecución:** local-first, apto para self-hosting
- **Infra:** compatibilidad con Docker Compose + Caddy + Redis/Chroma/Ollama

## Estado actual (Feb 2026)
- ✅ Scaffold público disponible
- ✅ README bilingüe (EN por defecto + ES)
- ✅ Base de CI + release configurada
- 🚧 Endurecimiento de funcionalidades en progreso

## Inicio rápido
```bash
git clone https://github.com/smouj/Noctumbra-Mail.git
cd Noctumbra-Mail
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.noctumbra_mail.cli --help
```

## Documentación
- [Guía de implementación](./docs/IMPLEMENTATION.md)
- [Arquitectura](./docs/ARCHITECTURE.md)
- [Runbook](./docs/RUNBOOK.md)
- [Guía de despliegue](./docs/DEPLOYMENT.md)
- [Proceso de releases](./docs/RELEASE.md)
- [Changelog](./CHANGELOG.md)

## Contribución
Las contribuciones son bienvenidas. Lee [CONTRIBUTING.md](./CONTRIBUTING.md).

## Licencia
MIT © 2026 smouj

---

### Otras skills
Explora el ecosistema completo aquí: **[smouj/smouj](https://github.com/smouj/smouj)**

**Firma:** [@Smouj013](https://x.com/smouj013)
