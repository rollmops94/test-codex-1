# ADR 20250826: initial-architecture

## Status
Accepted

## Context
The project starts as a simple Python script with a single entry point.

## Decision
Use a minimal structure with `main.py` as the executable module. Future modules can be added under a `src/` directory when needed.

## Consequences
- Simple to run and maintain.
- Lacks modular structure until expanded.
