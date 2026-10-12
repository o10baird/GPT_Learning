---
title: GPT Learning Syllabus
program: gpt_learning
document_role: live_curriculum_status
context_revision: 5
last_updated: 2026-10-12
progress_as_of: 2026-10-12
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

**Progress as of 2026-10-12**

- Current phase: `00_prep`
- Program state: preparation recovery overlapping the opening of the formal October 2026 curriculum
- User-reported USC SHIELD capstone focus: **Autonomous Warfare Command**
- Active deliverable: Prep ML Workflow
- Verified completed learning outcomes: none identified in the available repository/context evidence
- Verified repository evidence: learning-program structure, project briefs, resource indexes, templates, environment conventions, and repository integration guidance exist
- Current near-term focus: NumPy/pandas fluency, Git/testing/reproducibility, linear algebra, probability/statistics, and first reproducible classical-ML workflow
- Verified execution status: Todoist shows the Sep 21–Oct 4 prep tasks still open after an approximately one-week pause reported by the learner.
- Recovery schedule: complete foundational backlog Oct 12–18 and Prep ML Workflow Oct 19–23; begin the Q1 Coursera course after prep closes. Integrate capstone framing into the existing SHIELD synthesis/review time rather than adding separate hours.
- First USC SHIELD residency window has passed; the Residency 1 synthesis remains open in Todoist and should capture the Autonomous Warfare Command capstone framing without adding a separate workload stream.
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
| Autonomous Warfare Command | `autonomous-command-integration` | Analyze an autonomous command concept as a socio-technical C2 system: decision rights, human-machine roles, information/network architecture, uncertainty, resilience, assurance evidence, and strategic/policy implications | Active integration lens |

## Operating constraints

- Normal independent-learning budget: **6–8 hours/week**.
- During USC SHIELD residency/live-session weeks, SHIELD replaces most independent technical study.
- Complete **at least one Coursera course per federal fiscal-year quarter**.
- Use public, unclassified, or otherwise appropriately releasable information for all personal learning artifacts and cloud/commercial tooling.
- Prefer one primary instructional resource at a time; books, O'Reilly, Stanford material, and papers are supplements rather than parallel full courses.
- Progress is judged by explanation, application, and evaluation supported by evidence—not by reading completion, generated solutions, or course certificates alone.
- Autonomous Warfare Command is a cross-cutting application lens embedded in existing coursework; it does **not** add a separate weekly workload.

## Autonomous Warfare Command cross-cutting strategy

Treat the SHIELD capstone as the integrative problem that gives the technical curriculum a consistent application context. Focus on **command architecture and decision quality**, not operational weapon-employment tactics.

| Curriculum area | Capstone tie-in | Evidence to seek |
|---|---|---|
| Math/statistics | uncertainty, calibration, reliability, thresholds, tradeoffs under incomplete information | explain how uncertainty changes a command decision or assurance claim |
| Classical ML | prediction vs decision, asymmetric error costs, distribution shift, model confidence | baseline + error analysis tied to decision consequences |
| Causal inference | effects of autonomy/delegation policies, human-machine teaming interventions, experimental design | DAG or identification argument distinguishing prediction from causal effect |
| Network science | centralized/distributed C2, communication dependencies, robustness, failure propagation | public/synthetic graph analysis comparing architectural tradeoffs |
| Deep learning / vision | perception reliability, sensor fusion, degraded conditions, confidence, human oversight | failure analysis under shift/noise with explicit limits |
| Graph ML | agent/sensor/command relationships, distributed coordination, task allocation | compare graph and non-graph representations/baselines |
| Temporal graphs | changing communication/tasking networks, latency, dynamic dependencies | time-respecting evaluation with leakage controls |
| MLOps | edge deployment, provenance, monitoring, drift, rollback, resilient updates | reproducible pipeline plus assurance/rollback plan |
| USC SHIELD | doctrine, deterrence, escalation, command authority, accountability, acquisition, leadership | sourced capstone analysis connecting technical evidence to strategic choices |

### Recurring capstone questions

Use these questions to connect coursework to the capstone without creating additional assignments:

- What decisions are delegated, retained, or escalated, and on what evidence?
- What information must flow between humans, autonomous agents, sensors, and command nodes?
- How does the architecture degrade when communications, sensors, models, or nodes fail?
- How should confidence, uncertainty, and disagreement affect human-machine handoffs?
- What verification, validation, test, evaluation, and monitoring evidence is sufficient for a given level of delegation?
- How do autonomy and machine speed change deterrence, escalation risk, accountability, and mission command?
- Which claims are descriptive, predictive, causal, or normative, and what methods are valid for each?

All technical demonstrations for this strand must use public, synthetic, or appropriately releasable information. Prefer architecture, assurance, resilience, decision-support, and systems-analysis problems over tactical or weapon-employment detail.

## Quarterly Coursera requirement

| Quarter | Required completed course | Target completion | Program role | Status |
|---|---|---:|---|---|
| FY27 Q1: Oct–Dec 2026 | University of Michigan — *Applied Social Network Analysis in Python* | 2026-12-15 | Classical network analysis, NetworkX, centrality, connectivity, link prediction | Planned |
| FY27 Q2: Jan–Mar 2027 | University of Michigan — *Network Modeling and Analysis in Python* | 2027-03-14 | Communities, network models, diffusion, influence | Planned |
| FY27 Q3: Apr–Jun 2027 | DeepLearning.AI — *Convolutional Neural Networks* | 2027-06-20 | CNNs, transfer learning, detection, segmentation | Planned |
| FY27 Q4: Jul–Sep 2027 | DeepLearning.AI — *Machine Learning in Production* | 2027-09-12 | Production ML lifecycle, monitoring, drift, deployment reasoning | Planned |

Target dates are intentionally before quarter-end to provide schedule margin.

## 12-month syllabus

### Preparation recovery — through October 23, 2026

**Primary outcome:** `prep-reproducible-workflow`

**Learning objective:** establish the minimum technical and workflow baseline needed for the formal year.

**Planned work**
- NumPy and pandas refresher
- Git/GitHub refresher
- root `uv` environment and reproducible notebook workflow
- linear algebra and probability/statistics review
- first public-data baseline workflow
- initial error analysis and reproducibility checks

**Estimated effort:** Oct 12–18 approximately 7 h; Oct 19–23 approximately 5.5 h, leaving capacity to begin the Q1 Coursera course that weekend. Oct 5–11 is reserved primarily for USC SHIELD.

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
- October 5–11: SHIELD preparation/residency; no attempt to catch up technical backlog.
- October 12–23: finish deferred prep foundations and the Prep ML Workflow.
- October 24 onward: begin graph representation, connectivity, and NetworkX basics in *Applied Social Network Analysis in Python*.
- November: centrality, network measures, DAGs, confounding, potential outcomes; where useful, frame examples around command-network robustness, delegation, and human-machine decision policies
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
- January: communities, cohesion, assortativity, structural roles; compare centralized and distributed command-network structures using public/synthetic examples
- February: generative network models and diffusion; use diffusion/robustness concepts to reason about information propagation, coordination, and failure in autonomous C2
- March: influence models, temporal framing, neural-network prerequisites; connect temporal/network concepts to changing communications, tasking, and command dependencies

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
- May: CNN fundamentals, architectures, transfer learning; emphasize perception reliability, calibration, and human oversight rather than task-specific weapon applications
- June: detection/segmentation, model evaluation, failure analysis, certificate completion; analyze distribution shift, degraded sensing, and confidence as autonomy-assurance problems

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
- heterogeneous/multi-agent relationships relevant to distributed command architectures
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
- changing communication/tasking/command dependencies
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
- assurance-oriented logging, provenance, rollback, and degraded-connectivity considerations for edge/autonomous systems
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
| 2026-10-04 | Prep execution status | Todoist inspection found all Sep 21–Oct 4 prep tasks still open; learner reported taking approximately the prior week off | Todoist project `GPT_Learning` | Schedule evidence only; no mastery inference |
| 2026-10-12 | Autonomous Warfare Command capstone scope | Learner reported USC SHIELD capstone focus on Autonomous Warfare Command; Daily Reading Brief updated to support this lens | user report + automation configuration | Scope/strategy evidence only; capstone research question and deliverable requirements not yet inspected |

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

