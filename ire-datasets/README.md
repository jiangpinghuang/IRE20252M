# IRE-Datasets

IRE-Datasets stores data assets for intelligent requirements engineering research and benchmark construction.

## Dataset Categories

- **Project ideas**: short informal project descriptions and stakeholder goals.
- **Clarification dialogues**: multi-round analyst-stakeholder conversations.
- **User requirement lists**: user-facing needs, goals, and constraints.
- **System requirement lists**: structured functional and non-functional requirements.
- **Environment lists**: domain context, deployment environment, external systems, and operational constraints.
- **Requirement graphs**: nodes and edges representing goals, requirements, constraints, conflicts, rationale, and traceability.
- **Conflict cases**: contradictory, ambiguous, incomplete, or infeasible requirement examples.
- **SRS documents**: full or partial software requirements specifications.
- **Architecture mappings**: links between requirements and architectural components or decisions.
- **Executable tasks**: implementation, validation, test, or planning tasks derived from requirements.

## Dataset Construction

Dataset construction should track:

- Source and license.
- Collection method.
- Schema version.
- Processing pipeline.
- Known limitations.
- Intended benchmark task.

Raw data should remain under `raw/`; normalized and benchmark-ready data should be stored under `processed/` or task-specific directories.

## Annotation Workflow

Annotation guidelines should define:

- Label definitions.
- Examples and counterexamples.
- Annotator instructions.
- Quality control checks.
- Disagreement resolution.
- Version history.

## Quality Control

Dataset quality should be checked through schema validation, duplicate detection, consistency checks, annotation agreement where applicable, and manual review of high-impact examples.

## Future Benchmark Usage

Datasets should be designed so they can support IRE-Bench tasks, group papers, and the integrated ChatREQ master paper. Every dataset should state which research questions and benchmark tasks it can support.

