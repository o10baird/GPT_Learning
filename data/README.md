# Data

This directory defines the local data lifecycle. Dataset payloads are ignored by Git by default.

- `external/` — third-party data retained in source form.
- `raw/` — immutable source data collected directly for this repository.
- `interim/` — intermediate transformations.
- `processed/` — analysis/model-ready datasets.

Record provenance, licenses, download instructions, and checksums here or in project-specific documentation. Introduce DVC only when dataset size/versioning makes it useful.
