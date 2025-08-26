# Prompts

## Add new function
- **Role**: Contributor
- **Context**: `main.py`, `docs/STYLE_GUIDE.md`
- **Output**: Patch adding function with tests and updated docs.

## Regenerate API reference
- **Role**: Documentation bot
- **Context**: `docs/MODULE_INDEX.md`, `src/**/*.py` or `main.py`
- **Output**: Updated `docs/API_REFERENCE.md`.

## Refactor with ADR
- **Role**: Maintainer
- **Context**: Relevant source files, `docs/DESIGN_DECISIONS/`
- **Output**: Code changes and new ADR documenting rationale.
