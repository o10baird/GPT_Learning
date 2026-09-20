---
title: GPT Learning Syllabus
program: gpt_learning
document_role: live_curriculum_status
context_revision: 3
last_updated: 2026-09-20
progress_as_of: 2026-09-20
program_start: 2026-10-01
program_end: 2027-09-30
weekly_budget: 6-8 hours
status: active
---

# GPT Learning Syllabus — 2026–2027

## Purpose

This is the live syllabus and high-level status document for the 12-month technical learning program in data science, machine learning, computer vision, dynamic/temporal network analysis, graph machine learning, causal inference, and MLOps.

It serves four purposes:

1. define the planned sequence of learning;
2. show the current program phase and quarterly milestones;
3. record verified evidence of completed learning at the program level; and
4. provide a stable link between coursework, Obsidian synthesis, and Git artifacts.

This file is **not** the execution task tracker. Todoist project `GPT_Learning` remains authoritative for dated tasks, due dates, durations, and completion status. Obsidian remains authoritative for weekly learning logs, durable conceptual notes, literature synthesis, and project reasoning.

## Current status

**Progress as of 2026-09-20**

- Current phase: `00_prep`
- Program state: preparation before the formal October 2026 curriculum
- Active deliverable: Prep ML Workflow
- Verified completed learning outcomes: none identified in the available repository/context evidence
- Verified repository evidence: learning-program structure, project briefs, resource indexes, templates, environment conventions, and repository integration guidance exist
- Current near-term focus: NumPy/pandas fluency, Git/testing/reproducibility, linear algebra, probability/statistics, and first reproducible classical-ML workflow
- Known scheduling constraints: travel September 22–25; first USC SHIELD residency dominates October 5–11
- Detailed weekly-review evidence: **not inspected in this update**. The latest review identified by the portable context is `20 - Moments/Learning Logs/2026/2026-W38 Learning Review.md`; its contents must be supplied or connected before this file is updated from that evidence.

### Status vocabulary

| Status | Meaning |
|---|---|
| Planned | Scheduled in the curriculum; no completion evidence yet |
| Active | Currently being worked |
| Evidence pending | User reports completion/progress, but durable evidence has not yet been inspected |
| Complete | Completion is supported by inspected evidence |
| Deferred | Deliberately moved to preserve workload or prerequisites |

## Program outcomes

| Strand | Outcome ID | Demonstration expected | Status |
|---|---|---|---|
| Prep | `prep-reproducible-workflow` | Explain and reproduce a small NumPy/pandas-to-baseline workflow with appropriate checks | Active |
| Math/statistics | `math-stats-foundations` | Solve worked examples and connect them to model behavior and uncertainty | Planned |
| Classical ML | `classical-ml-evaluation` | Compare baseline and learned models, justify validation, and analyze errors/leakage | Planned |
| Causal inference | `causal-identification` | State a causal question and explain identification assumptions and sensitivity | Planned |
| Network science | `network-analysis` | Explain graph construction and interpret structural measures with caveats | Planned |
| Deep learning | `deep-learning-training` | Train a small model, diagnose optimization/generalization, and reproduce the run | Planned |
| Computer vision | `vision-error-analysis` | Evaluate a vision baseline, inspect failures, and discuss deployment limitations | Planned |
| Graph ML | `graph-ml-evaluation` | Compare graph/non-graph baselines and justify representation and split choices | Planned |
| Temporal graphs | `temporal-graph-validation` | Preserve temporal order and explain changing networks and leakage risks | Planned |
| MLOps | `mlops-reproducibility` | Package, test, reproduce, and monitor a model with a deployment/rollback plan | Planned |
| Integrated capstone | `integrated-capstone` | Combine methods into an explained, reproducible system with a limitations report | Planned |
| USC SHIELD | `shield-policy-integration` | Produce sourced analysis connecting technical evidence, uncertainty, strategy, and policy tradeoffs | Planned |

## Operating constraints

- Normal independent-learning budget: **6–8 hours/week**.
- During USC SHIELD residency/live-session weeks, SHIELD replaces most independent technical study.
- Complete **at least one Coursera course per federal fiscal-year quarter**.
- Use public, unclassified, or otherwise appropriately releasable information for all personal learning artifacts and cloud/commercial tooling.
- Prefer one primary instructional resource at a time; books, O'Reilly, Stanford material, and papers are supplements rather than parallel full courses.
- Progress is judged by explanation, application, and evaluation supported by evidence—not by reading completion, generated solutions, or course certificates alone.

## Quarterly Coursera requirement

| Quarter | Required completed course | Target completion | Program role | Status |
|---|---|---:|---|---|
| FY27 Q1: Oct–Dec 2026 | University of Michigan — *Applied Social Network Analysis in Python* | 2026-12-15 | Classical network analysis, NetworkX, centrality, connectivity, link prediction | Planned |
| FY27 Q2: Jan–Mar 2027 | University of Michigan — *Network Modeling and Analysis in Python* | 2027-03-14 | Communities, network models, diffusion, influence | Planned |
| FY27 Q3: Apr–Jun 2027 | DeepLearning.AI — *Convolutional Neural Networks* | 2027-06-20 | CNNs, transfer learning, detection, segmentation | Planned |
| FY27 Q4: Jul–Sep 2027 | DeepLearning.AI — *Machine Learning in Production* | 2027-09-12 | Production ML lifecycle, monitoring, drift, deployment reasoning | Planned |

Target dates are intentionally before quarter-end to provide schedule margin.

## 12-month syllabus

### Preparation — now through September 2026

**Primary outcome:** `prep-reproducible-workflow`

**Learning objective:** establish the minimum technical and workflow baseline needed for the formal year.

**Planned work**
- NumPy and pandas refresher
- Git/GitHub refresher
- root `uv` environment and reproducible notebook workflow
- linear algebra and probability/statistics review
- first public-data baseline workflow
- initial error analysis and reproducibility checks

**Estimated effort:** 6–8 h/week, reduced during September 22–25 travel.

**Evidence of completion**
- learner can explain the data flow and validation choices;
- notebook or script runs from the documented environment;
- checks/tests are present where appropriate;
- limitations/errors are recorded;
- reusable logic is promoted into `src/gpt_learning/` when justified.

**Git destination:** `coursework/00_prep/` and relevant reusable code under `src/gpt_learning/`.

**Obsidian destination:** weekly review under `20 - Moments/Learning Logs/2026`; durable concepts under `50 - Knowledge/Concepts`; project reasoning under `30 - Projects/GPT Learning/Prep ML Workflow.md`.

**Status:** Active.

---

### October–December 2026 — Network-analysis foundation + causal reasoning

**Primary outcomes:** `network-analysis`, `causal-identification`, continued `math-stats-foundations`

**Primary structured course:** *Applied Social Network Analysis in Python*.

**Supporting resources**
- Wasserman & Faust — *Social Network Analysis: Methods and Applications*
- Larry Wasserman — *All of Statistics*
- Deisenroth, Faisal, and Ong — *Mathematics for Machine Learning*
- Scott Cunningham — *Causal Inference: The Remix*
- DoD MWR O'Reilly as targeted reference
- USC SHIELD strategic/policy work

**Planned progression**
- October: graph representation, connectivity, NetworkX basics; keep independent load light around SHIELD residency/live sessions
- November: centrality, network measures, DAGs, confounding, potential outcomes
- December: network evolution/link prediction, course final work, certificate completion, synthesis

**Estimated effort:** 6–8 h/week normally; 0–2 h of independent work during heavy SHIELD weeks.

**Evidence of completion**
- explain why a graph representation is appropriate for a chosen public-data problem;
- compute and interpret structural measures with caveats;
- demonstrate at least one link-prediction or network-evolution exercise;
- state one causal question using a DAG and identify plausible confounders/colliders;
- Coursera certificate by target date.

**Git destination:** `coursework/04_network_science/` and, where useful, `projects/graph_temporal/`.

**Obsidian destination:** `60 - Sources/Courses`, `50 - Knowledge/Concepts`, course sessions under `20 - Moments/Course Sessions`, and weekly reviews.

**Status:** Planned.

---

### January–March 2027 — Network modeling, diffusion, and deep-learning preparation

**Primary outcomes:** `network-analysis`, `deep-learning-training`, continued `causal-identification`

**Primary structured course:** *Network Modeling and Analysis in Python*.

**Supporting resources**
- Wasserman & Faust
- Cunningham, especially panel/difference-in-differences concepts where relevant
- Géron — selected neural-network foundations
- *Mathematics for Machine Learning* — vector calculus/optimization refresh

**Planned progression**
- January: communities, cohesion, assortativity, structural roles
- February: generative network models and diffusion
- March: influence models, temporal framing, neural-network prerequisites

**Estimated effort:** 6–8 h/week normally, reduced during SHIELD sessions.

**Evidence of completion**
- compare multiple community/network-generation methods;
- explain assumptions behind a diffusion model;
- extend a public graph into a time-indexed representation without temporal leakage;
- Coursera certificate by target date.

**Git destination:** `coursework/04_network_science/`, then preparatory work in `coursework/05_deep_learning/`.

**Obsidian destination:** network concepts, causal distinctions, course-session records, weekly reviews.

**Status:** Planned.

---

### April–June 2027 — Deep learning and computer vision

**Primary outcomes:** `deep-learning-training`, `vision-error-analysis`

**Primary structured course:** DeepLearning.AI *Convolutional Neural Networks*.

**Supporting resources**
- Géron — neural networks and CNN chapters
- Stanford CS231n — selected challenge material only
- *Mathematics for Machine Learning* — gradients/optimization as needed
- *Concepts, Models, and Tools for Information Fusion* — uncertainty/sensor-fusion context
- CVAT/FiftyOne where annotation and visual error analysis are useful

**Workload adjustment:** April remains intentionally light until the USC SHIELD capstone is complete. The main CNN course load begins after the SHIELD completion period.

**Planned progression**
- April: SHIELD capstone priority; maintain technical continuity only
- May: CNN fundamentals, architectures, transfer learning
- June: detection/segmentation, model evaluation, failure analysis, certificate completion

**Estimated effort:** April 0–3 h/week independent; May–June 6–8 h/week.

**Evidence of completion**
- train and reproduce a small vision model;
- explain optimization/generalization behavior;
- inspect representative errors rather than reporting aggregate metrics only;
- document deployment/data limitations;
- Coursera certificate by target date.

**Git destination:** `coursework/05_deep_learning/`, `coursework/06_computer_vision/`, and `projects/vision_system/`.

**Obsidian destination:** concept notes, source synthesis, project reasoning, weekly reviews.

**Status:** Planned.

---

### July 2027 — Graph machine learning

**Primary outcome:** `graph-ml-evaluation`

**Primary resources**
- Stanford CS224W — selected graph-ML/GNN material
- PyTorch Geometric official tutorials/documentation
- O'Reilly references as needed

**Planned progression**
- node embeddings
- message passing
- GCN
- GraphSAGE
- graph attention
- link prediction
- appropriate graph train/validation/test splits

**Estimated effort:** 7–8 h/week.

**Evidence of completion**
- implement at least one non-neural graph baseline and one GNN;
- justify graph representation and split design;
- compare models on a common task;
- explain where leakage can occur in graph ML.

**Git destination:** `coursework/07_graph_ml/` and `projects/graph_temporal/`.

**Obsidian destination:** durable graph-ML concepts and project reasoning.

**Status:** Planned.

---

### August 2027 — Temporal graph learning + causal synthesis

**Primary outcome:** `temporal-graph-validation`, continued `causal-identification`

**Primary resources**
- Temporal Graph Benchmark
- PyTorch Geometric Temporal / relevant current libraries
- selected temporal-graph papers
- Cunningham panel and difference-in-differences material

**Planned progression**
- snapshot vs event-based temporal representations
- temporal link prediction
- dynamic node representations
- time-respecting splits and leakage prevention
- distinguish forecasting from causal effect estimation

**Estimated effort:** 7–8 h/week.

**Evidence of completion**
- build or analyze a temporally ordered graph dataset;
- preserve temporal order in evaluation;
- explain at least one dynamic-network result with uncertainty/caveats;
- explicitly distinguish predictive and causal claims.

**Git destination:** `coursework/08_temporal_graphs/` and `projects/graph_temporal/`.

**Obsidian destination:** temporal-network concepts, causal synthesis, project reasoning.

**Status:** Planned.

---

### September 2027 — MLOps + integrated capstone

**Primary outcomes:** `mlops-reproducibility`, `integrated-capstone`

**Primary structured course:** DeepLearning.AI *Machine Learning in Production*.

**Supporting resources via DoD MWR O'Reilly**
- Chip Huyen — *Designing Machine Learning Systems*
- Kleppmann & Riccomini — *Designing Data-Intensive Applications*, 2nd ed.
- *Machine Learning Design Patterns*
- Reis & Housley — *Fundamentals of Data Engineering*
- *Practical MLOps*

**Supporting implementation resources**
- MLflow
- DVC or equivalent data/model versioning where justified
- Docker
- FastAPI
- GitHub Actions
- monitoring tooling appropriate to the project
- Full Stack Deep Learning selected labs

**Estimated effort:** 7–8 h/week.

**Evidence of completion**
- package and reproduce a model from a clean environment;
- automated tests/checks run reliably;
- model is containerized and served or otherwise deployed in a reproducible way;
- experiment/model lineage is recorded;
- monitoring and rollback/recovery approach is documented;
- final limitations report explains technical and analytical weaknesses;
- Coursera certificate by target date.

**Git destination:** `coursework/09_mlops/` and `projects/mlops_capstone/`.

**Obsidian destination:** MLOps concepts, architectural reasoning, final project synthesis, program retrospective.

**Status:** Planned.

## Resource policy

### Primary structured instruction
- Coursera: one completed course per quarter
- USC SHIELD: October 2026–April 2027, replacing most independent study during residency/live-session weeks

### Primary owned texts
- *Mathematics for Machine Learning*
- *All of Statistics*
- *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*
- *Social Network Analysis: Methods and Applications*
- *Computer Systems: A Programmer's Perspective*

### Targeted references
- DoD MWR O'Reilly: use by problem, not as another parallel course
- Lay and DeVore for remediation/exercises
- *Machine Learning Pocket Reference*
- information-fusion, numerical-analysis, vector-analysis, error-analysis, and statistical-test references as needed

### Advanced free supplements
- Stanford CS231n
- Stanford CS224W
- Full Stack Deep Learning
- official NumPy/pandas/PyTorch/PyG documentation
- *Causal Inference: The Remix*

## Weekly workload template

### Normal week — 6–8 hours
- 2–3 h structured course or primary instructional material
- 1 h targeted reading
- 2–3 h independent implementation
- 0.5 h research/current technical reading
- 0.5 h synthesis/review

### SHIELD residency/live-session week
- 0–2 h independent technical work
- no new technical module unless capacity is clearly available
- prioritize SHIELD notes, capstone work, and recovery of the normal schedule afterward

### Post-SHIELD project-intensive week
- 1.5–2 h structured instruction
- 0.5–1 h reading
- 4–5 h implementation/evaluation
- 0.5 h synthesis/review

## Evidence ledger

This table records only inspected or otherwise clearly identified program-level evidence. Detailed weekly evidence belongs in Obsidian; implementation artifacts belong in Git.

| Date | Outcome | Evidence | Location | Assessment |
|---|---|---|---|---|
| 2026-09-20 | Program setup only | Repository structure, environment conventions, project briefs, vault integration guidance | repository + portable context | Infrastructure evidence; **not** evidence of technical mastery |
| 2026-09-20 | `prep-reproducible-workflow` | No completed exercise artifact identified in available repository/context review | — | Active; completion not yet demonstrated |

## Maintenance rules

Update this file when any of the following occurs:

- a phase starts, completes, or is materially rescheduled;
- a quarterly Coursera course starts or completes;
- inspected evidence supports completion of a learning outcome;
- SHIELD scheduling materially changes available independent-study capacity;
- a project scope or major resource changes;
- the current program focus changes.

When updating status:
- distinguish **verified evidence**, **user-reported progress**, **plans**, and **assumptions**;
- do not mark an outcome complete solely because a course or reading was completed;
- link to Git artifacts when they exist;
- use the latest relevant Obsidian weekly review for progress when its contents are available;
- leave detailed dated task execution in Todoist.

## Systems of record

| System | Authoritative for |
|---|---|
| Todoist | dated tasks, due dates, durations, execution status |
| Obsidian | concepts, synthesis, weekly reviews, project reasoning, course-session notes |
| Zotero | PDFs, bibliographic metadata, annotations/highlights |
| GitHub | code, notebooks, tests, environment, technical reports, CI/CD, this live program syllabus |
| ChatGPT | planning, tutoring, sequencing, workload adjustment |
| Codex / VS Code | implementation, debugging, refactoring, repository maintenance |

## Next review trigger

At the next planning review, update this syllabus from:
1. the latest weekly review in Obsidian;
2. inspected Git artifacts produced since 2026-09-20;
3. user-reported status clearly labeled as such;
4. Todoist only for execution status if explicitly connected/read.

