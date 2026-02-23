# Noctumbra-Mail

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![License](https://img.shields.io/github/license/smouj/Noctumbra-Mail)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Noctumbra-Mail)
![CI](https://img.shields.io/badge/CI-planned-lightgrey)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/smouj013_dev)

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

**Zero-touch inbox operations for stealth communication workflows.**

## Visión
Noctumbra-Mail es una skill orientada a producción dentro del **Universo SuperAgentes de smouj**. Está diseñada para resolver un problema operativo concreto con ejecución local-first, trazas de razonamiento transparentes y controles de seguridad prácticos. La arquitectura prioriza herramientas gratuitas/open-source, comportamiento determinista e integración modular con otras skills autónomas.

## Superpoder principal
- ⚡ **Intent-aware triage and safe auto-response orchestration**

## Estado actual (Febrero 2026)
- 🚧 Fase de ideación y scaffolding robusto
- Próximos hitos:
  - [ ] Finalizar contratos de dominio e interfaces
  - [ ] Publicar un comando CLI mínimo ejecutable
  - [ ] Añadir perfil de modelo local Ollama y estrategia de fallback
  - [ ] Implementar un ejemplo completo end-to-end
  - [ ] Añadir puertas de calidad (lint, typecheck, test)
  - [ ] Publicar arquitectura y runbook operativo

## Arquitectura planeada (stack gratuito/open-source)
- **Lenguaje principal:** Python 3.11+
- **Framework agente:** AutoGen
- **Modelos locales:** Ollama (Llama 3.1, Qwen2.5, DeepSeek-Coder, Mistral)
- **Dependencias clave:** google-api-python-client, imapclient, jinja2, pydantic, tenacity
- **Modelo de ejecución:** local-first, despliegue self-hosted opcional

## Blueprint de capacidades
- ✅ Inbox classification
- ✅ Draft generation
- ✅ Escalation policies
- ✅ Calendar extraction
- ✅ Spam-safe automation


## Estructura del proyecto
```text
Noctumbra-Mail/
├── src/noctumbra_mail/
│   ├── core/           # orquestación de dominio y políticas
│   ├── adapters/       # integraciones externas y puentes de herramientas
│   ├── memory/         # estado, recuperación y estrategias de contexto
│   └── cli.py          # interfaz de comandos local para operación
├── docs/
│   ├── IMPLEMENTATION.md
│   ├── ARCHITECTURE.md
│   └── RUNBOOK.md
├── examples/
├── tests/
├── requirements.txt
└── README.md
```

## Inicio rápido
```bash
git clone https://github.com/smouj/Noctumbra-Mail.git
cd Noctumbra-Mail
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
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
- [Contribución](./CONTRIBUTING.md)

## Contribución
Las contribuciones son bienvenidas. Lee **CONTRIBUTING.md** antes de abrir issues o PRs.

## Licencia
MIT © 2026 smouj
