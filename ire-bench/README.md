# IRE-Bench

IRE-Bench is the benchmark infrastructure for intelligent requirements engineering.

## Benchmark Philosophy

IRE-Bench should evaluate end-to-end requirements engineering capabilities, not only isolated text generation. Tasks should measure whether a method can produce useful, traceable, consistent, feasible, and reviewable requirements artifacts.

Benchmarks should be:

- Reproducible across model and system versions.
- Grounded in realistic requirements engineering scenarios.
- Connected to datasets, knowledge sources, and paper claims.
- Designed with baselines and ablations from the beginning.
- Usable by future student groups and external researchers.

## Benchmark Tasks

Initial tasks include:

- Clarification question generation.
- Environment-aware requirement generation.
- Requirement graph construction.
- Conflict detection and consistency checking.
- Human-in-the-loop intervention selection.
- Feasibility validation.
- Requirement-to-architecture mapping.
- Requirement-to-task transformation.

## Baseline Systems

Baseline systems may include:

- Single-prompt LLM baselines.
- Retrieval-augmented LLM baselines.
- Rule-based RE checks.
- Traditional NLP classifiers.
- Graph-only reasoning methods.
- Human-authored reference workflows.
- ChatREQ ablations with disabled agents or knowledge sources.

## Evaluation Protocols

Each benchmark task should define:

- Input schema.
- Expected output schema.
- Dataset split.
- Ground truth or annotation procedure.
- Metrics.
- Baselines.
- Human evaluation criteria where needed.
- Reproducibility package.

## Metrics

IRE-Bench tracks:

- **Completeness**: coverage of required information, constraints, stakeholders, and acceptance conditions.
- **Consistency**: absence of contradictions across requirements and assumptions.
- **Conflict rate**: number and severity of detected or introduced conflicts.
- **Traceability**: quality of links among goals, requirements, sources, architecture, tests, and tasks.
- **Feasibility**: alignment with resources, platforms, deployment conditions, and technical constraints.
- **Human effort**: amount and difficulty of human intervention required.
- **Downstream utility**: usefulness of generated artifacts for architecture, implementation, testing, or planning.

## Reproducibility Requirements

Benchmark results should include dataset version, code version, prompt version, knowledge base version, model or baseline configuration, random seeds where applicable, and scripts for producing paper-ready tables.

