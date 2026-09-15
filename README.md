# GPT_Learning

Year-long technical learning repository for data science, machine learning, computer vision, network science, graph/temporal ML, causal inference, and MLOps.

## Tool boundaries

- **Zotero**: source PDFs, bibliographic metadata, highlights, and annotations.
- **Obsidian**: durable concept notes, literature synthesis, learning logs, and project reasoning.
- **Todoist**: dated actions and workload management.
- **ChatGPT**: learning strategy, tutoring, and syllabus adjustment.
- **VS Code + Codex**: coding, notebooks, testing, and refactoring.
- **Git/GitHub**: executable work, technical documentation, configuration, and reproducibility.

General notes and PDFs should not be stored in this repository.

## Repository layout

- `src/gpt_learning/` — reusable Python code promoted from coursework and projects.
- `tests/` — tests for reusable code.
- `coursework/` — learning exercises organized by technical phase.
- `projects/` — substantial standalone projects with their own reproducible environments when needed.
- `data/` — local data staging; large/raw data are ignored by Git.
- `configs/` — experiment and application configuration.
- `scripts/` — repeatable command-line utilities.
- `reports/` — reproducible analytical reports, figures, and rendered outputs.
- `bibliography/` — machine-readable bibliography exported from Zotero; Zotero remains the source of truth.
- `docs/` — software architecture and technical decision records.
- `infra/` — Docker and deployment assets.
- `.github/workflows/` — CI workflows introduced during the MLOps phase.

## Python environment

The root project is intended to use `uv` with a repository-local `.venv/`. Serious later projects may use independent `uv` environments under their project directories.

Do not commit `.venv/`, secrets, large datasets, model weights, or experiment artifacts.
