# AGENTS.md

Read the shared rules first: agents/AGENTS.md of https://github.com/DE-Knowledge-Base/agents.md (on Alamin's MacBooks at ~/agents.md), plus the applicable harness supplement. This file adds this repository's guidance.

Read [BenchmarkInstructions.md](BenchmarkInstructions.md) before applicable work; their existing project protocols remain applicable.

## Purpose, current state and planned work

A local research fork comparing Ookla open speed-test data with Statistics Canada internet-availability material, including documented data-processing and Streamlit workflows.

Current maintenance and runtime/deployment status are not established by this limited audit, so `repo.yaml` uses `state: unknown`. Current capabilities identify documented or source-visible material; they are not application-test claims.

Current documented capabilities:

- README and BenchmarkInstructions.md document data processing, benchmark setup and a Streamlit application; scripts/, src/, notebooks/ and streamlit/ are tracked.
- Fork comparison records a local experiment-notebook commit, establishing local analysis work; its results were not inspected.

Documented planned work (completion not established by this audit):

- README explicitly leaves the end-to-end results pipeline untested; start-to-finish verification remains a documented gap.

## Working here

- Read README.md and BenchmarkInstructions.md for an authorized analysis/benchmark task; preserve upstream attribution and data provenance.
- Benchmark cleanup/install/download commands are not executed by this metadata task. Destructive cleanup, environment changes and large data transfers need their applicable approval; no notebook result or runtime performance is verified here.
