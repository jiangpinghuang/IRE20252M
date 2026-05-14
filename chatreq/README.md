# ChatREQ

ChatREQ is the core knowledge-driven multi-agent system for end-to-end intelligent requirements engineering.

## Scope

ChatREQ is intended to support:

- Requirement elicitation and clarification.
- Environment-aware requirement generation.
- Requirement graph construction.
- Conflict detection and consistency checking.
- Human-in-the-loop review.
- Feasibility validation.
- Requirement-to-architecture alignment.
- Executable task planning.

## Directory Overview

| Path | Purpose |
| --- | --- |
| `agents/` | Agent roles, coordination logic, and role-specific policies. |
| `knowledge/` | Local knowledge used by ChatREQ workflows. |
| `artifacts/` | Generated or curated RE artifacts. |
| `workflows/` | End-to-end and module-level workflow definitions. |
| `evaluation/` | System-level evaluation hooks and outputs. |
| `datasets/` | ChatREQ-local dataset samples or adapters. |
| `docs/` | System documentation. |
| `examples/` | Example projects, inputs, and generated outputs. |
| `prompts/` | Prompt templates and agent instructions. |
| `configs/` | Runtime and experiment configurations. |
| `tests/` | Unit, integration, and regression tests. |

## Research Expectations

New ChatREQ modules should define their task, inputs, outputs, knowledge dependencies, failure modes, evaluation metrics, and relationship to IRE-Bench.

