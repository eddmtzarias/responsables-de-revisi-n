# responsables-de-revisión

Repositorio para centralizar las responsabilidades de revisión del proyecto. Aquí se almacenan las políticas, workflows y recursos para gestionar revisiones de PRs e issues.

## Objetivo
Facilitar el triage y la asignación de revisores, automatizar respuestas iniciales a issues/PRs y proporcionar una guía clara para colaboradores y mantenedores.

## Contenido inicial
- .github/CODEOWNERS — define responsables de revisión
- .github/workflows/ci.yml — CI para ejecutar tests
- CONTRIBUTING.md — guía para contribuir
- tests/ — tests de ejemplo

## Quick start (local)
1. Clona el repositorio:
   git clone https://github.com/eddmtzarias/responsables-de-revisi-n.git
2. Crea un entorno virtual e instala dependencias:
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
3. Ejecuta tests:
   pytest

## Cómo contribuir
Revisa CONTRIBUTING.md. Para cambios importantes crea un issue antes de trabajar y abre un PR desde una rama feature/*.

## Contacto
Mantenedor: @eddmtzarias
