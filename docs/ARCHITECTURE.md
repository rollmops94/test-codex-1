# Architecture

This project is a minimal Python application. It currently consists of a single module, `main.py`, which provides a `main()` entry point.

## Layers
- **CLI Layer**: `main.py` provides a command-line entry point that prints a message.

## High-level Data Flow
1. User runs `python main.py`.
2. The `main()` function executes and prints a confirmation message to standard output.

## Extension Points
- Add new modules under `src/` or additional functions in `main.py`.
- Future CLI commands can be registered in `main.py` within the `main()` function.

## Internal Dependencies
- None beyond the standard library.

## External Dependencies
- Python 3.11 or later.

## Related ADRs
- [Initial Architecture](DESIGN_DECISIONS/ADR-20250826-initial-architecture.md)
