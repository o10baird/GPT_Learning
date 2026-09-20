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
- keep weekly learning logs concise, dated, and evidence-focused; execution status remains in Todoist
- use the existing numbered vault folders; express program/phase/subject relationships through metadata and MOCs
- use the existing Basic Note, Project, Literature Note, and Weekly Review templates plus Course Session
- preserve canonical concepts, source attribution, legacy provenance, and verified path-qualified links
- keep future briefs and review stubs distinct from completed work or demonstrated learning
- link Obsidian learning reasoning to repository technical decision records instead of duplicating authoritative records
- do not mirror the Git repository structure into Obsidian

## Cross-chat documentation and handoff

Keep `docs/learning_context.md` understandable without repository or Obsidian access. It must contain essential program conventions, system responsibilities, the vault mapping, and learning-evidence criteria. The vault's Metadata Schema and templates remain authoritative for their detailed conventions; summarize the planning-relevant parts in the portable brief.

When implementing a durable workflow or structural change:

- Update `docs/learning_context.md` in the same change, recording its revision/date and a concise change summary.
- Distinguish proposed, implemented, and verified items; verify paths before describing files as existing.
- Preserve curriculum constraints, exact reading assignments when relocating them, and unrelated user content.
- Preserve template filenames or repair their references when a change requires renaming.
- Update affected README links and vault entry points so the changed workflow is discoverable.
- Validate changed Markdown links, metadata, phase/outcome identifiers, and cross-system references as appropriate. Documentation-only changes do not require unrelated Python test runs.

When preparing a handoff to ChatGPT, include the context revision, progress-as-of date, completed changes with artifact references, coursework implications, and remaining proposals or questions. Preserve user-reported versus directly inspected evidence. Do not equate code generation, scaffolds, note counts, or reading completion with mastery.

If ChatGPT lacks current execution records, provide a compact dated snapshot derived from available evidence. Keep detailed logs in Obsidian and dated actions in Todoist. A snapshot in the portable brief is an explicitly dated export, not a second live tracker.

Maintain `docs/chatgpt_project_instructions.md` as the short instruction block for the external ChatGPT learning project. Identify which sources need refreshing after a local revision. Report synchronization only when actually verified; editing local files does not refresh uploaded copies.

Do not infer account access, task completion, or permission to change remote project settings from a path, project name, or plugin listed in documentation. When the work is a proposal, provide a concrete amendment and label it as proposed; when implementation is requested, apply authorized changes and accurately report their scope.

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
