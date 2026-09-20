# AGENTS.md

## Purpose

This repository is part of a year-long technical learning program. Before making structural or workflow changes, read:

- `docs/learning_context.md`
- `README.md`

Use `docs/learning_context.md` as the canonical cross-chat description of learning goals, current phase, tool responsibilities, and repository conventions.

## Systems of record

### Obsidian is authoritative for

- conceptual notes
- literature synthesis
- weekly learning logs
- durable course notes
- project reasoning and cross-links

Do not duplicate general learning notes into this repository.

### Zotero is authoritative for

- PDFs
- bibliographic metadata
- source annotations/highlights
- citation keys

Do not add article/book PDFs to this repository.

### Todoist is authoritative for

- dated tasks
- due dates
- durations
- execution status

Do not recreate task tracking as Markdown checklists in the repository unless a checklist is intrinsic to a technical artifact.

### GitHub repository is authoritative for

- code
- notebooks
- tests
- configuration
- Python environment definitions
- technical reports
- CI/CD
- architecture and technical decision records

## Repository rules

1. Keep one root uv project for general coursework.
2. The root `pyproject.toml` lives at repository root.
3. `src/gpt_learning/` is the importable package, not a separate uv project.
4. General-coursework notebooks belong under:
   `coursework/<phase>/notebooks/`
5. Reusable code belongs under:
   `src/gpt_learning/`
6. Significant standalone projects may have their own `pyproject.toml`, `uv.lock`, and `.venv`; initialize them with `uv init --no-workspace` unless a real workspace is intentionally desired.
7. Never commit `.venv/`, secrets, large raw datasets, model weights, or local experiment caches.
8. Prefer `uv add` and `uv add --dev` over manual `pip install` for project dependencies.
9. Use `pytest` for tests and `ruff` for linting/formatting.
10. Keep notebook code exploratory; move reusable logic into `src/` and add tests.

## Coding-assistant behavior

When helping with exercises:

- Prefer hints, diagnostics, tests, and review before providing a complete solution.
- Do not replace the learning objective with generated code the user cannot explain.
- If generating code, keep it small, idiomatic, and testable.
- Explain important tradeoffs and non-obvious behavior.
- Encourage reproducibility and clean environment management.
- When fixing a bug, identify the root cause rather than only patching symptoms.

## Obsidian integration

When asked to build or modify the Obsidian vault:

- use the vault structure and conventions in `docs/learning_context.md`
- favor concept-oriented notes over course-only notes
- keep literature notes distinct from concept notes
- link related concepts rather than duplicating explanations
- keep weekly learning logs concise and execution-focused
- do not mirror the Git repository structure into Obsidian

## Safety / data handling

All work in this repository and connected personal tooling must use public, unclassified, or otherwise appropriately releasable information.

Do not place controlled, operational, sensitive, or restricted data into:

- GitHub
- ChatGPT/Codex
- personal cloud environments
- Kaggle
- commercial MLOps tools
- public notebooks

## When context is stale

If `docs/learning_context.md` conflicts with current explicit user instructions, follow the current user instruction and update the context file if the change is durable.
