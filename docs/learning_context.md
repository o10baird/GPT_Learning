# Learning Context

## Purpose

This file is the canonical cross-chat context for the year-long learning program. ChatGPT should use it for curriculum strategy and planning. Codex should use it to understand the learning plan when structuring or updating the Obsidian vault and related technical artifacts.

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

## Obsidian conventions

Recommended vault structure:

```text
Learning/
├── 00 Dashboard/
├── 10 Courses/
│   ├── USC SHIELD/
│   ├── Coursera/
│   └── OReilly/
├── 20 Concepts/
│   ├── Mathematics/
│   ├── Statistics/
│   ├── Machine Learning/
│   ├── Causal Inference/
│   ├── Computer Vision/
│   ├── Networks/
│   └── MLOps/
├── 30 Literature/
├── 40 Projects/
├── 50 Learning Log/
└── 90 Templates/
```

Principles:

- Course notes are temporary organizational structures.
- Concept notes are the durable long-term knowledge layer.
- Prefer one concept per note with links to related concepts.
- Literature notes should synthesize sources in the user's own words rather than dump highlights.
- Weekly learning logs should capture planned work, completed work, lessons learned, unresolved questions, technical problems, and next-week adjustments.

## Current travel-adjusted schedule

Travel: September 22-25, 2026.

Near-term plan:

- Sep 21: complete NumPy/pandas refresher/reference notebook
- Sep 22: non-coding geometry review
- Sep 23: non-coding eigenvalues/eigenvectors/SVD review
- Sep 24: non-coding probability review
- Sep 25: travel synthesis
- Sep 26: Git/testing/reproducibility refresher
- Sep 27: vectors, matrices, basis, rank
- Sep 28: Bernoulli simulation + covariance/correlation/noise
- Sep 29: mathematical checkpoint
- Sep 30: dataset selection + exploratory analysis
- Oct 1: baseline ML model
- Oct 2: error analysis
- Oct 3: make prep ML project reproducible
- Oct 4: prep-phase retrospective
- Oct 5-11: first formal week, dominated by USC SHIELD residency

## Current reading assignments

### NumPy/pandas refresher
Use as reference while coding:

- NumPy Quickstart: basics, shape manipulation, copies/views, broadcasting
- pandas *10 minutes to pandas*: object creation, viewing, selection, missing data, operations, merge, grouping, reshaping

### Geometry
*Mathematics for Machine Learning*, Chapter 3:

- §3.1 Norms
- §3.2 Inner Products
- §3.3 Lengths and Distances
- §3.4 Angles and Orthogonality
- §3.8 Orthogonal Projections

### Matrix decompositions
*Mathematics for Machine Learning*, Chapter 4:

- §4.2 Eigenvalues and Eigenvectors
- §4.4 Eigendecomposition and Diagonalization
- §4.5 Singular Value Decomposition
- optional: §4.6 Matrix Approximation

### Probability
*All of Statistics*:

- §1.5 Independent Events
- §1.6 Conditional Probability
- §1.7 Bayes' Theorem
- §§2.1-2.4
- §§3.1-3.3

### Git refresher
*Pro Git*, Chapter 2:

- §2.1 Getting a Git Repository
- §2.2 Recording Changes to the Repository
- §2.3 Viewing the Commit History
- §2.4 Undoing Things

### Linear algebra
*Mathematics for Machine Learning*, Chapter 2:

- skim §2.2 Matrices
- read §2.4 Vector Spaces
- read §2.5 Linear Independence
- read §2.6 Basis and Rank

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
- current 2-4 week schedule
