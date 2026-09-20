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

## Learning context and vault integration

Read [Learning Context](docs/learning_context.md) for the curriculum, workload constraints, Unified Knowledge Vault mapping, outcome evidence, and dated progress snapshot. [AGENTS.md](AGENTS.md) defines repository work and documentation-maintenance rules.

For planning chats outside Codex, supply the current learning context and relevant dated review, then use [ChatGPT Project Instructions](docs/chatgpt_project_instructions.md). Local edits and uploaded project sources must be refreshed separately; the context records the current refresh status.

The vault's Learning Dashboard is at `00 - Home/Learning Dashboard.md` within `C:\Users\Ian_Baird\Obsidian_Vaults\Unified Knowledge Vault`.

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
- `docs/` — software architecture, technical decisions, and the portable learning-program brief.
- `infra/` — Docker and deployment assets.
- `.github/workflows/` — CI workflows introduced during the MLOps phase.

## Python environment

The root project is intended to use `uv` with a repository-local `.venv/`. Serious later projects may use independent `uv` environments under their project directories.

Do not commit `.venv/`, secrets, large datasets, model weights, or experiment artifacts.
