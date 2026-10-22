---
context_revision: 6
last_updated: 2026-10-21
progress_as_of: 2026-10-21
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
- Autonomous Warfare Command as the USC SHIELD capstone integration theme, emphasizing command architecture, human-machine teaming, resilient distributed C2, autonomy assurance, and strategic/policy implications

## Program horizon

- Formal 12-month learning program: October 2026 through September 2027
- Normal independent-learning budget: 6-8 hours per week
- Employer requirement: complete at least one Coursera course per federal fiscal-year quarter during the formal program year
- USC SHIELD runs in parallel from October 2026 through April 2027
- During USC residency/live-session weeks, USC replaces most independent technical study rather than being added on top
- Temporary capacity adjustment: work/travel limits independent learning through 2026-10-29; keep 2026-10-30 through 2026-11-01 deliberately light, then return to the normal 6-8 hour weekly ceiling

## Current verified execution state (progress as of 2026-10-21)

Preparation recovery remains active while the formal program begins. Direct Todoist inspection shows the NumPy/pandas refresher and USC SHIELD Residency 1 synthesis marked complete; their underlying artifacts were not inspected in this update, so these are execution-status facts rather than mastery determinations. Nine prep tasks remained open on 2026-10-21.

User-reported constraints:
- work demands have limited study;
- travel continues through 2026-10-29.

Near-term strategy:
- no scheduled coursework through 2026-10-29;
- keep 2026-10-30 through 2026-11-01 to a single 30-minute re-entry checkpoint;
- spread the remaining prep backlog across November at roughly 1-2 hours per week alongside the Coursera course;
- start University of Michigan's *Applied Social Network Analysis in Python* in November and complete it by 2026-12-13, ahead of the employer's FY27 Q1 deadline.

## Live syllabus convention

The repository now maintains `docs/syllabus.md` as the live program-level syllabus and status document. It records the planned 12-month sequence, quarterly Coursera milestones, phase-level status, and inspected evidence at the program level. It must not duplicate Todoist's dated task execution or Obsidian's detailed learning logs. Update it when a phase starts/completes, a quarterly Coursera course changes status, inspected evidence supports an outcome update, SHIELD materially changes available capacity, or a major project/resource changes.

For status updates in the syllabus, preserve the distinction between verified evidence, user-reported progress, plans, and assumptions. Course/reading completion alone is not evidence of mastery.

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

## Autonomous Warfare Command capstone integration

**Status:** user-reported capstone focus as of 2026-10-12. This is a cross-cutting application lens, not a separate workload stream.

Use the technical curriculum to examine Autonomous Warfare Command as a socio-technical command-and-control problem rather than as a weapons-employment problem. The recurring analytical frame is:

- **Command authority and decision rights:** what decisions remain human, what may be delegated, what triggers escalation or override, and how mission command changes under autonomy.
- **Information and network architecture:** centralized versus distributed C2, communication dependencies, latency, information quality, resilience, and graceful degradation.
- **Human-machine teaming:** workload, trust calibration, supervisory control, handoffs, explainability, and responsibility.
- **Multi-agent autonomy:** coordination, task allocation, distributed control, emergent behavior, and robustness at the architectural/analytical level.
- **Perception and uncertainty:** sensor fusion, confidence/calibration, out-of-distribution behavior, degraded sensing, and uncertainty propagation.
- **Assurance and test/evaluation:** verification/validation, simulation, scenario coverage, fail-safe behavior, red teaming, adversarial robustness, and evidence needed to justify deployment.
- **Production/edge ML:** model/data versioning, monitoring, drift, rollback, cyber/software supply-chain concerns, and operation under intermittent or contested communications.
- **Strategic and policy effects:** deterrence, escalation, tempo, accountability, legal/ethical constraints, acquisition, organizational design, and command responsibility.

Tie each technical phase to the capstone where it creates genuine analytical leverage:

| Technical strand | Autonomous Warfare Command tie-in |
|---|---|
| Math/statistics | uncertainty, calibration, reliability, decision thresholds, tradeoffs under incomplete information |
| Classical ML | prediction versus decision, baselines, error costs, distribution shift, confidence and decision-support limits |
| Causal inference | effects of delegation, human-machine teaming policies, interventions, and experimental/wargaming designs |
| Network science | C2 topology, robustness, centralization/decentralization, communication dependencies, failure propagation |
| Deep learning / vision | perception reliability, sensor fusion, confidence, degraded conditions, human oversight |
| Graph ML | heterogeneous agent/sensor/command relationships, coordination, task allocation, representation choices |
| Temporal graphs | changing C2/communication/tasking networks, latency, dynamic dependencies, time-respecting validation |
| MLOps | edge deployment, assurance, provenance, monitoring, rollback, model updates, resilient lifecycle management |
| USC SHIELD | doctrine, strategy, deterrence, escalation, leadership, industry, acquisition, governance, command authority |

Any personal technical experimentation must use public, synthetic, or otherwise appropriately releasable data and should emphasize architecture, assurance, decision quality, and resilience rather than operational tactics or weapon-employment details.

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

- Coursera — primary structured course platform; FY27 Q1 course is University of Michigan's *Applied Social Network Analysis in Python*, beginning in November 2026 with planned completion by 2026-12-13
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
- source-specific literature notes
- multi-moment syntheses integrating several days, course sessions, or earlier syntheses
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
| Weekly, residency, course, travel, phase, or thematic integration | `20 - Moments/Syntheses/YYYY` |
| Program outcomes and finite deliverables | `30 - Projects/GPT Learning` |
| Ongoing technical learning responsibility | `40 - Areas` |
| Durable concepts and synthesized claims | `50 - Knowledge/Concepts` |
| Course overviews and interpretation of individual external sources | `60 - Sources/Courses` and `60 - Sources/Literature Notes` |
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
| Multi-moment synthesis index | `20 - Moments/Syntheses/Syntheses.md` |
| Workflow and handoff guide | `99 - System/Learning Workflow.md` |
| Initial weekly review | `20 - Moments/Learning Logs/2026/2026-W38 Learning Review.md` |
| Preserved schedule and readings | `20 - Moments/Learning Logs/2026/2026-09-20 Prep Planning Snapshot.md` |

Existing integration points include `80 - Atlas/Machine Learning MOC.md`, `80 - Atlas/Decision Science and Risk.md`, and `80 - Atlas/Strategy and Security.md`.

The program and prep project are active. The three future capstone briefs are marked `someday`: their note scaffolds exist, while datasets, final scope, success thresholds, implementations, and results remain open. Additional subject MOCs are deferred until enough notes justify them. The SHIELD overview records program context; it is not a verified syllabus.

The shared `Basic Note.md` (concept), `Project.md`, `Literature Note.md`, and `Weekly Review.md` templates were extended in `99 - System/Templates`; `Course Session.md` was added. Existing filenames and core Templates configuration are retained.

Revision 3 adds `Synthesis.md`, `Weekly Synthesis.md`, and `Course Overview.md` in the same template folder, plus the synthesis index/year folder and dashboard navigation. These are implemented structures, not completed coursework notes. No additional plugin is required; Dataview navigation is optional.

### Canonical notes and source handling

Use one canonical note per concept. Search available curated notes, aliases, and legacy material before proposing a new one; identify unverified titles and links as proposed.

Relevant legacy notes and review stubs can be processed during coursework. Consult `50 - Knowledge/Canonical Conflicts/Canonical Conflict Index.md` for relevant title conflicts. Preserve provenance using `source_vault`, `source_path`, and source links. Review stubs and routing notes are not established explanations or learning evidence; do not treat the entire migration backlog as a prerequisite for study.

Course-session and daily records can feed one multi-moment synthesis; source-specific interpretation stays in literature notes, and reusable explanations belong in canonical concept notes. Preserve source attribution; link learning reasoning to technical artifacts and Git architecture decision records. Keep each authoritative record in its designated system.

### Multi-moment synthesis conventions

A synthesis explains what several inputs mean together: connections, tensions, changed understanding, evidence, and remaining questions. It is not a literature note or just a list of activities. Keep original moments as evidence and link reusable takeaways into concept/project notes without duplicating the full argument.

- Weekly: `20 - Moments/Syntheses/YYYY/YYYY-Www Learning Synthesis.md`, using the ISO week-year and week covered, not the date written or Todoist deadline. Use `Weekly Synthesis.md`.
- Other scopes: stable descriptive names, such as `USC SHIELD Residency 1 Synthesis.md` or `Prep Phase Synthesis.md`, under `20 - Moments/Syntheses/YYYY`. Use `Synthesis.md`. The year is the coverage end-year, or creation year if open/unknown; retain the path when extending the note. Distinguish repeated trips/cohorts with an identifying period in the title.
- Set `type: synthesis`, `synthesis_scope` (`week`, `course`, `residency`, `travel`, `phase`, or `theme`), `period_start`, and `period_end`. Coverage is inclusive; weekly coverage is Monday–Sunday. Leave unknown dates blank. `created` and `modified` record writing dates separately.
- `inputs` is a list of quoted, path-qualified wikilinks to notes actually used. Daily notes, course sessions, learning logs, source notes, and earlier syntheses can all contribute; no self-links or circular chains. Queries show candidates/navigation, not evidence that a note was used.
- `courses` is a list of zero, one, or several verified course-overview links on synthesis notes. Individual session/source notes retain singular `course`.
- Use a single weekly synthesis for integration, reflection, and planning when sufficient. A separate `Weekly Review.md` note is optional and should link to the synthesis instead of repeating it. Phase/course syntheses may build on weekly notes.
- Search for an existing note of the same scope/period, including former names, before creating one. Preserve content and repair links when moving an existing note. Do not invent input links, coursework, or evidence just to populate a template.

Naming example only: October 5–11, 2026 maps to `20 - Moments/Syntheses/2026/2026-W41 Learning Synthesis.md`, even if written October 12. This example is not an asserted existing study note.

### Learning metadata and templates

The vault's `99 - System/Metadata Schema.md` remains authoritative for detailed metadata. This portable summary supplies conventions needed for planning:

- `program: gpt_learning` identifies program records.
- `phase` uses a repository identifier: `00_prep`, `01_math_stats`, `02_classical_ml`, `03_causal_inference`, `04_network_science`, `05_deep_learning`, `06_computer_vision`, `07_graph_ml`, `08_temporal_graphs`, or `09_mlops`.
- `learning_outcomes` is a list of stable identifiers from the outcome table below. Multiple outcomes may span phases.
- `course` is a verified link to a course overview; `provider` records its known provider.
- Synthesis notes use plural `courses` and explicit `inputs`; coverage dates are distinct from creation/modification dates as described above.
- `repo_path` is relative to the repository root. `artifact_links` stays empty until actual evidence can be referenced.
- Reuse the existing `type`, `status`, `up`, `related`, `citekey`, and `zotero_uri` properties.
- A source's `reading_status` is `unread`, `reading`, or `read`; its note lifecycle `status` is separate.
- Course overviews use `type: source` and `source_type: course`; sessions use `type: event`; operational weekly logs use `type: review`; multi-moment integration uses `type: synthesis`.
- Weekly reviews/syntheses use the ISO `week` covered. A review's `date` is when it happened; a synthesis uses coverage dates and actual `created` / `modified`. A completed review or synthesis describes the record, not mastery of its outcomes.
- Concept templates prompt for explanation, assumptions, a worked example, failure mode, evidence, and meaningful connections. Synthesis templates connect multiple inputs and capture changes in understanding; optional review sections capture capacity and next-week adjustments.

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
| Autonomous Warfare Command | `autonomous-command-integration` | Analyze an autonomous command concept as a socio-technical C2 system by specifying decision rights, human-machine roles, information/network architecture, uncertainty, resilience, assurance evidence, and strategic/policy implications. |

These are program evidence expectations, not assertions of completed competence or official external-course assessment criteria.

For each substantial outcome, identify a concept explanation in the learner's own words, integration of relevant sessions/sources, an applied artifact or analysis, assumptions/errors/remaining gaps, and a connection to another subject or project. Code-bearing work includes reproduction instructions and appropriate checks. One artifact may support several outcomes. Match the evidence to the subject: SHIELD may produce a sourced policy analysis rather than code.

Treat successful explanation, application, and evaluation as evidence; reading completion, generated solutions, scaffolds, and note counts alone are insufficient.

## Last verified learning-progress snapshot

**Progress as of: 2026-10-21.** Source: the existing program context plus direct inspection of Todoist project `GPT_Learning` on 2026-10-21. This small snapshot is provided for chats without vault access; it is not a substitute for the latest Obsidian weekly review.

- Current phase: `00_prep` recovery overlapping the formal program.
- Active deliverable: Prep ML Workflow; intended output remains a reproducible public-data baseline with error analysis.
- Verified Todoist execution evidence: the NumPy/pandas refresher was marked complete on 2026-10-13 and the USC SHIELD Residency 1 synthesis was marked complete on 2026-10-12. Their artifacts were not inspected here, so no learning outcome is marked complete from those task states alone.
- Verified Todoist backlog on 2026-10-21: nine prep tasks remained open.
- User-reported capacity constraint: work demands have limited progress and travel continues through 2026-10-29.
- Temporary recovery schedule now implemented in Todoist: no coursework through Oct 29; one 30-minute mathematical re-entry checkpoint on Nov 1; remaining prep work distributed across Nov 2-29.
- FY27 Q1 Coursera plan now implemented in Todoist: *Applied Social Network Analysis in Python* begins Nov 7, is spread across Modules 1-4 through Dec 13, and has an explicit Dec 15 deadline. Coursera currently describes the course as four modules totaling about 26 hours; use the course platform as the authoritative source if its estimates change.
- Weekly workload from Nov 2 onward remains within the 6-8 hour ceiling by interleaving roughly 1-2 hours of prep with Coursera rather than finishing the entire prep backlog first.
- Autonomous Warfare Command remains the SHIELD capstone integration lens for network robustness, centralization, dynamic networks, assurance, and human-machine command relationships.
- Latest Obsidian weekly review/synthesis content was not inspected in this update; provide it when evidence of learning, misconceptions, or capacity needs to be incorporated.

Todoist project `GPT_Learning` remains the system of record for dated actions. On 2026-10-21 nine existing tasks were rescheduled and eight Coursera module work blocks were created/adjusted to implement the November-December plan.
## Guidance for ChatGPT

Use this document for program design and the latest dated progress evidence for execution context. Current explicit user instructions supersede older program guidance. Compare context revisions and progress dates; do not silently treat an older upload or conversation recollection as current state.

Plan within the normal 6–8 hour weekly budget, including synthesis and review. Adjust independent study during SHIELD residency/live-session weeks.

For each substantial assignment, specify its learning outcome, estimated effort, evidence of completion, and destination in Obsidian or Git. Prefer hints, questions, and diagnostics before complete exercise solutions unless the user requests a complete solution.

For work integrating several moments/sessions, specify a synthesis scope/period, exact vault-relative filename, appropriate synthesis template, and input records to consult. Do not route combined course work into Literature Note. Preserve existing task dates and completion status when only note instructions change; proposed new scheduling is separate. One weekly synthesis can include the learning reflection and next steps.

When local files or services are unavailable, use the supplied context, label assumptions and proposed changes, and request only the missing material needed for the task. Distinguish content drafted in chat from changes actually saved. A local path, project name, or documented plugin does not establish access.

At the end of a planning session that changes durable conventions, supply the exact documentation amendment for Codex and a concise handoff: context revision, progress-as-of date, completed changes/evidence, coursework implications, and remaining proposals or questions. Preserve the distinction between inspected evidence and user-reported progress.

## Sharing context outside Codex

Provide the current version of this file in the ChatGPT learning project's sources and paste the instruction block from [chatgpt_project_instructions.md](chatgpt_project_instructions.md) into its project instructions. Include the latest relevant dated synthesis, review, or source excerpt when progress or detailed assignments matter. In a standalone chat, supply the same context directly.

Project sources and instructions can be shared across related chats, but a ChatGPT project does not itself provide access to the local repository or vault. See [official project documentation](https://learn.chatgpt.com/docs/projects).

Local edits do not establish that uploaded copies were refreshed. After a durable revision, refresh the supplied copy and confirm its revision/date. Record synchronization as completed only when verified. If using a connected source, verify which version was retrieved.

**External ChatGPT refresh status for revision 4:** pending; no project uploads, project instructions, memory, or account/plugin settings were changed by this repository/Todoist update.
**External ChatGPT refresh status for revision 3:** pending; local context and instruction-file edits do not update project uploads, online project instructions, or account/plugin settings.

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
Obsidian multi-moment synthesis → reusable concept/project notes
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

- **Revision 6 — 2026-10-21:** recorded the work/travel interruption through Oct 29; lightened the schedule through Nov 1; rescheduled the remaining prep backlog across November; and moved the FY27 Q1 Coursera course start into November with *Applied Social Network Analysis in Python* planned for completion by Dec 13 while preserving the 6-8 hour weekly ceiling.
- **Revision 5 — 2026-10-12:** recorded the user-reported USC SHIELD capstone focus on Autonomous Warfare Command; added a cross-cutting autonomous-command analytical frame and learning outcome; mapped technical strands to the capstone; recorded the updated Daily Reading Brief integration without adding a separate workload stream.
- **Revision 4 — 2026-10-04:** recorded the learner-reported pause and verified Todoist backlog; rescheduled prep recovery to Oct 12–23 around the first SHIELD residency while preserving the Q1 Coursera completion target; updated the live syllabus accordingly.
- **Revision 3 — 2026-09-20:** added `docs/syllabus.md` as the live program-level syllabus/status artifact; recorded the quarterly Coursera completion constraint and maintenance rules that preserve Todoist and Obsidian as the execution/evidence systems of record.
- **Revision 3 — 2026-10-12:** separated multi-moment synthesis from source-specific literature notes; added synthesis folders/templates, coverage-based weekly naming, explicit input/course links, optional combined weekly reflection, and updated cross-chat task-routing guidance. Preserved the dated learning-progress snapshot; refreshed study evidence has not been assessed.
- **Revision 2 — 2026-09-20:** integrated learning with the existing Unified Knowledge Vault; added learning outcome/evidence expectations, verified entry points, metadata/template conventions, a dated progress snapshot, and explicit ChatGPT handoff rules. Preserved the previous schedule and reading assignments in the vault's dated prep planning snapshot.
