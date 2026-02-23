# Runbook — Noctumbra-Mail

## Local setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Basic command
```bash
python -m src.noctumbra_mail.cli --help
```

## Troubleshooting
- Check Python version (3.11+)
- Recreate virtualenv if dependency conflicts occur
- Run tests before opening an issue

## Release checklist
- [ ] Lint passes
- [ ] Typecheck passes
- [ ] Tests pass
- [ ] README and docs updated
- [ ] Version tag and changelog note
