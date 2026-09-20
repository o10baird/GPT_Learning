---
context_revision: 2
last_updated: 2026-09-20
progress_as_of: 2026-09-20
---

# Learning Context

## Purpose

This file is the canonical portable brief for the year-long learning program. It is designed to be understood in ChatGPT without direct repository or vault access. ChatGPT uses it for curriculum strategy, tutoring, and planning; Codex uses it for implementation and documentation maintenance. Detailed knowledge, source records, and live task status remain in the systems of record below.

## Current objectives

Primary technical goals:

- Data science and statistical learning
- Computer vision
- Dynamic and temporal network analysis
- Graph machine learning and graph neural networks
- Causal inference
- MLOps and production machine-learning systems

Supporting foundations:

- Linear algebra
- Probability and statistics
- Software engineering and reproducibility
- Systems and data engineering
- Strategic and policy reasoning through USC SHIELD

## Program horizon

- Formal 12-month learning program: October 2026 through September 2027
- Normal independent-learning budget: 6-8 hours per week
- USC SHIELD runs in parallel from October 2026 through April 2027
- During USC residency/live-session weeks, USC replaces most independent technical study rather than being added on top

## Current phase

Preparation / mathematical and analytical foundations before the formal October curriculum.

Current near-term emphasis:

- NumPy and pandas fluency
- Git, testing, and reproducibility
- Linear algebra refresh
- Probability/statistics refresh
- First reproducible classical-ML workflow
- Preparation for the first USC SHIELD residency

## Current learning sequence

1. Preparation and environment setup
2. Mathematical and statistical foundations
3. Classical machine learning
4. Causal inference
5. Network science
6. Deep learning foundations
7. Computer vision
8. Graph machine learning
9. Temporal graph learning
10. MLOps and production systems
11. Integrated capstone

## Primary learning resources

### Existing books

- Deisenroth, Faisal, and Ong — *Mathematics for Machine Learning*
- Larry Wasserman — *All of Statistics*
- Aurélien Géron — *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*
- Wasserman and Faust — *Social Network Analysis: Methods and Applications*
- Bryant and O'Hallaron — *Computer Systems: A Programmer's Perspective*
- Lay — *Linear Algebra and Its Applications*
- DeVore — *Probability and Statistics for Engineering and the Sciences*
- *Concepts, Models, and Tools for Information Fusion*
- *Machine Learning Pocket Reference*
- supporting numerical-analysis, vector-analysis, error-analysis, and statistical-reference texts

### Online/platform resources

- Coursera — primary structured course platform
- DoD MWR O'Reilly — technical reference library
- USC SHIELD — strategic/engineering/policy integration
- Stanford CS231n — advanced computer-vision supplement
- Stanford CS224W — graph-ML supplement
- Full Stack Deep Learning — production/deployment supplement
- *Causal Inference: The Remix* — causal-inference reading
- official NumPy/pandas/PyTorch/PyG documentation as implementation references

## Tool responsibilities

### Zotero
System of record for:

- PDFs
- bibliographic metadata
- source-specific highlights and annotations
- citation keys

### Obsidian
System of record for:

- durable conceptual notes
- literature synthesis
- weekly learning logs
- project reasoning
- cross-linked knowledge
- course/session notes that should persist beyond the course

### Todoist
System of record for:

- dated learning tasks
- durations
- task execution status
- links to relevant notes, sources, and code

Current Todoist project: `GPT_Learning`

### ChatGPT
Primary role:

- learning strategy
- curriculum design
- sequencing
- workload adjustment
- tutorial explanations
- review questions
- weekly replanning based on progress

ChatGPT conversation history is not the canonical source of learning state; this file and the systems above are.

### Codex + VS Code
Primary role:

- coding
- notebook implementation
- refactoring
- testing
- debugging
- repository maintenance
- implementation assistance

### Sublime Text
Use only for:

- quick scratch editing
- inspecting text/CSV/JSON/YAML
- one-off text transformations

If content matters long term, move it to Obsidian or Git.

### GitHub repository
System of record for:

- code
- notebooks
- tests
- environment definitions
- reproducible reports
- CI/CD configuration
- architecture and technical decision records

General learning notes and PDFs should not be duplicated into Git.

## Repository conventions

Repository: `o10baird/GPT_Learning`

Core layout:

```text
GPT_Learning/
├── README.md
├── pyproject.toml
├── uv.lock
├── .python-version
├── .gitignore
├── .env.example
├── src/
│   └── gpt_learning/
├── tests/
├── coursework/
│   ├── 00_prep/
│   ├── 01_math_stats/
│   ├── 02_classical_ml/
│   ├── 03_causal_inference/
│   ├── 04_network_science/
│   ├── 05_deep_learning/
│   ├── 06_computer_vision/
│   ├── 07_graph_ml/
│   ├── 08_temporal_graphs/
│   └── 09_mlops/
├── projects/
│   ├── vision_system/
│   ├── graph_temporal/
│   └── mlops_capstone/
├── data/
├── configs/
├── scripts/
├── reports/
├── bibliography/
├── docs/
├── infra/
└── .github/
```

### Notebook placement

- learning exercise: `coursework/<phase>/notebooks/`
- project-specific experiment: `projects/<project>/notebooks/`
- reusable logic: `src/gpt_learning/`

### Python environment

- Root coursework environment: `GPT_Learning/.venv`
- Managed with `uv`
- Root project metadata lives only in `GPT_Learning/pyproject.toml`
- `src/gpt_learning/` is the importable Python package, not a separate uv project
- General coursework should use the single root environment
- Larger future projects may get standalone project environments with `uv init --no-workspace`

### Code-quality baseline

Use:

- `pytest` for tests
- `ruff` for linting/formatting
- Git commits with meaningful messages
- reproducible runs from a clean clone where practical

## Knowledge-management integration

The learning program uses **Unified Knowledge Vault** at
`C:\Users\Ian_Baird\Obsidian_Vaults\Unified Knowledge Vault`.

Its numbered folders organize notes by purpose. Curriculum phases and subjects are expressed through metadata, links, and Maps of Content (MOCs: curated topic indexes). Do not create a parallel top-level `Learning/` tree or mirror the repository hierarchy into the vault.

| Material | Vault destination |
|---|---|
| Operational dashboards | `00 - Home` |
| Unprocessed capture | `10 - Inbox` |
| Weekly learning logs and course-session records | `20 - Moments/Learning Logs/YYYY` and `20 - Moments/Course Sessions` |
| Program outcomes and finite deliverables | `30 - Projects/GPT Learning` |
| Ongoing technical learning responsibility | `40 - Areas` |
| Durable concepts and synthesized claims | `50 - Knowledge/Concepts` |
| Course overviews and literature synthesis | `60 - Sources/Courses` and `60 - Sources/Literature Notes` |
| Structured curriculum/resource inventories | `70 - Collections/Curriculum` |
| Program navigation and subject MOCs | `80 - Atlas` |
| Templates and metadata conventions | `99 - System` |

### Verified entry points and implementation status

The following are implemented locally in this revision. Paths are relative to the vault root and identify local notes; they do not grant a chat access to the files.

| Entry point | Vault-relative path |
|---|---|
| Learning dashboard | `00 - Home/Learning Dashboard.md` |
| Enduring learning area | `40 - Areas/Technical Learning.md` |
| Finite program | `30 - Projects/GPT Learning/GPT Learning 2026-2027.md` |
| Prep deliverable | `30 - Projects/GPT Learning/Prep ML Workflow.md` |
| Vision project brief | `30 - Projects/GPT Learning/Vision System.md` |
| Graph/temporal project brief | `30 - Projects/GPT Learning/Graph-Temporal Project.md` |
| MLOps capstone brief | `30 - Projects/GPT Learning/MLOps Capstone.md` |
| Curriculum and outcome definitions | `80 - Atlas/Learning Program MOC.md` |
| Resource inventory | `70 - Collections/Curriculum/GPT Learning Resources.md` |
| SHIELD source overview | `60 - Sources/Courses/USC SHIELD.md` |
| Course-session index | `20 - Moments/Course Sessions/Course Sessions.md` |
| Workflow and handoff guide | `99 - System/Learning Workflow.md` |
| Initial weekly review | `20 - Moments/Learning Logs/2026/2026-W38 Learning Review.md` |
| Preserved schedule and readings | `20 - Moments/Learning Logs/2026/2026-09-20 Prep Planning Snapshot.md` |

Existing integration points include `80 - Atlas/Machine Learning MOC.md`, `80 - Atlas/Decision Science and Risk.md`, and `80 - Atlas/Strategy and Security.md`.

The program and prep project are active. The three future capstone briefs are marked `someday`: their note scaffolds exist, while datasets, final scope, success thresholds, implementations, and results remain open. Additional subject MOCs are deferred until enough notes justify them. The SHIELD overview records program context; it is not a verified syllabus.

The shared `Basic Note.md` (concept), `Project.md`, `Literature Note.md`, and `Weekly Review.md` templates were extended in `99 - System/Templates`; `Course Session.md` was added. Existing filenames and core Templates configuration are retained.

### Canonical notes and source handling

Use one canonical note per concept. Search available curated notes, aliases, and legacy material before proposing a new one; identify unverified titles and links as proposed.

Relevant legacy notes and review stubs can be processed during coursework. Consult `50 - Knowledge/Canonical Conflicts/Canonical Conflict Index.md` for relevant title conflicts. Preserve provenance using `source_vault`, `source_path`, and source links. Review stubs and routing notes are not established explanations or learning evidence; do not treat the entire migration backlog as a prerequisite for study.

Course-session records feed durable concept and source notes. Preserve source attribution; link learning reasoning to technical artifacts and Git architecture decision records. Keep each authoritative record in its designated system.

### Learning metadata and templates

The vault's `99 - System/Metadata Schema.md` remains authoritative for detailed metadata. This portable summary supplies conventions needed for planning:

- `program: gpt_learning` identifies program records.
- `phase` uses a repository identifier: `00_prep`, `01_math_stats`, `02_classical_ml`, `03_causal_inference`, `04_network_science`, `05_deep_learning`, `06_computer_vision`, `07_graph_ml`, `08_temporal_graphs`, or `09_mlops`.
- `learning_outcomes` is a list of stable identifiers from the outcome table below. Multiple outcomes may span phases.
- `course` is a verified link to a course overview; `provider` records its known provider.
- `repo_path` is relative to the repository root. `artifact_links` stays empty until actual evidence can be referenced.
- Reuse the existing `type`, `status`, `up`, `related`, `citekey`, and `zotero_uri` properties.
- A source's `reading_status` is `unread`, `reading`, or `read`; its note lifecycle `status` is separate.
- Course overviews use `type: source` and `source_type: course`; sessions use `type: event`; weekly logs use `type: review`.
- Weekly logs use an explicit ISO `week` and actual `date`. A completed review describes the record, not mastery of its outcomes.
- Concept templates prompt for explanation, assumptions, a worked example, failure mode, evidence, and meaningful connections. Weekly reviews capture evidence, misconceptions, capacity, and next-week adjustments.

## Learning outcomes and evidence

| Phase or strand | Outcome identifier | Demonstration |
|---|---|---|
| Prep | `prep-reproducible-workflow` | Explain and reproduce a small NumPy/pandas-to-baseline workflow with appropriate checks. |
| Mathematics/statistics | `math-stats-foundations` | Solve worked examples and connect them to model behavior and uncertainty. |
| Classical ML | `classical-ml-evaluation` | Compare baseline and learned models, justify validation, and analyze errors/leakage. |
| Causal inference | `causal-identification` | State a causal question and explain identification assumptions and sensitivity. |
| Network science | `network-analysis` | Explain graph construction and interpret structural measures with caveats. |
| Deep learning | `deep-learning-training` | Train a small model, diagnose optimization/generalization, and reproduce the run. |
| Computer vision | `vision-error-analysis` | Evaluate a vision baseline, inspect failures, and discuss deployment limitations. |
| Graph ML | `graph-ml-evaluation` | Compare graph/non-graph baselines and justify representation and split choices. |
| Temporal graphs | `temporal-graph-validation` | Preserve temporal order and explain changing networks and leakage risks. |
| MLOps | `mlops-reproducibility` | Package, test, reproduce, and monitor a model with a deployment/rollback plan. |
| Integrated capstone | `integrated-capstone` | Combine methods into an explained, reproducible system with a limitations report. |
| USC SHIELD | `shield-policy-integration` | Produce sourced analysis connecting technical evidence, uncertainty, strategy, and policy tradeoffs. |

These are program evidence expectations, not assertions of completed competence or official external-course assessment criteria.

For each substantial outcome, identify a concept explanation in the learner's own words, source synthesis, an applied artifact or analysis, assumptions/errors/remaining gaps, and a connection to another subject or project. Code-bearing work includes reproduction instructions and appropriate checks. One artifact may support several outcomes. Match the evidence to the subject: SHIELD may produce a sourced policy analysis rather than code.

Treat successful explanation, application, and evaluation as evidence; reading completion, generated solutions, scaffolds, and note counts alone are insufficient.

## Current progress snapshot

**Progress as of: 2026-09-20.** Source: the existing program context and a local setup/file review. This small snapshot is provided for chats without vault access; it is not live task status.

- Current phase: `00_prep`.
- Active deliverable: Prep ML Workflow; intended output is a reproducible public-data baseline with error analysis.
- Confirmed system work: learning navigation, project briefs, source/resource indexes, templates, and repository integration guidance.
- Coursework evidence: none identified in the setup review; no learning outcome is marked complete. The phase and project directories exist, but no exercise artifacts were found.
- Near-term subjects: NumPy/pandas, Git/testing/reproducibility, linear algebra, probability/statistics, and SHIELD preparation.
- Upcoming constraints from the preserved plan: travel September 22–25; October 5–11 dominated by the first SHIELD residency.
- Open choices: public dataset, prediction question, metric, and actual SHIELD materials.
- Latest review and detailed prep assignments: the dated vault notes listed above. Supply their content to a chat when specific assignments or progress are needed.

Detailed dates and reading sections were preserved in the archived prep planning snapshot before being removed from this brief. Todoist project `GPT_Learning` remains the system of record for dated actions; it was not read or modified during this documentation integration. No task scheduling or account connection is implied.

## Guidance for ChatGPT

Use this document for program design and the latest dated progress evidence for execution context. Current explicit user instructions supersede older program guidance. Compare context revisions and progress dates; do not silently treat an older upload or conversation recollection as current state.

Plan within the normal 6–8 hour weekly budget, including synthesis and review. Adjust independent study during SHIELD residency/live-session weeks.

For each substantial assignment, specify its learning outcome, estimated effort, evidence of completion, and destination in Obsidian or Git. Prefer hints, questions, and diagnostics before complete exercise solutions unless the user requests a complete solution.

When local files or services are unavailable, use the supplied context, label assumptions and proposed changes, and request only the missing material needed for the task. Distinguish content drafted in chat from changes actually saved. A local path, project name, or documented plugin does not establish access.

At the end of a planning session that changes durable conventions, supply the exact documentation amendment for Codex and a concise handoff: context revision, progress-as-of date, completed changes/evidence, coursework implications, and remaining proposals or questions. Preserve the distinction between inspected evidence and user-reported progress.

## Sharing context outside Codex

Provide the current version of this file in the ChatGPT learning project's sources and paste the instruction block from [chatgpt_project_instructions.md](chatgpt_project_instructions.md) into its project instructions. Include the latest relevant dated review or source excerpt when progress or detailed assignments matter. In a standalone chat, supply the same context directly.

Project sources and instructions can be shared across related chats, but a ChatGPT project does not itself provide access to the local repository or vault. See [official project documentation](https://learn.chatgpt.com/docs/projects).

Local edits do not establish that uploaded copies were refreshed. After a durable revision, refresh the supplied copy and confirm its revision/date. Record synchronization as completed only when verified. If using a connected source, verify which version was retrieved.

**External ChatGPT refresh status for revision 2:** pending; no project uploads, project instructions, or account/plugin settings were changed by this local integration.

## Workflow

Preferred loop:

```text
ChatGPT planning
    ↓
Todoist scheduling
    ↓
Zotero / Coursera / O'Reilly / USC learning
    ↓
VS Code + Codex implementation
    ↓
Obsidian synthesis
    ↓
Git commit / project artifact
    ↓
weekly review and replanning
```

The principle is:

- plan in ChatGPT
- execute from Todoist
- read in Zotero / course platforms
- build in VS Code/Codex
- synthesize in Obsidian
- preserve technical work in GitHub
- review and replan weekly

## Data handling constraint

All personal learning work, cloud compute, GitHub repositories, ChatGPT/Codex use, Kaggle, and commercial tooling must remain based on public, unclassified, or otherwise appropriately releasable information. Do not move controlled, operational, sensitive, or restricted data into personal/commercial learning systems.

## Maintenance rule

Update this file when any of the following materially change:

- curriculum sequence
- current learning phase
- major tools or system-of-record assignments
- repository conventions
- Obsidian organization
- major project definitions
- durable capacity constraints and the dated progress snapshot needed for cross-chat planning

Update the context revision/date and record a concise change summary. Keep implementation statuses accurate; preserve detailed assignments before relocating them. Refresh the ChatGPT-supplied copy separately and report that refresh only when confirmed.

## Revision history

- **Revision 2 — 2026-09-20:** integrated learning with the existing Unified Knowledge Vault; added learning outcome/evidence expectations, verified entry points, metadata/template conventions, a dated progress snapshot, and explicit ChatGPT handoff rules. Preserved the previous schedule and reading assignments in the vault's dated prep planning snapshot.
