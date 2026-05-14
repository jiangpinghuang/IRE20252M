# Naming Convention

Consistent naming keeps papers, datasets, benchmarks, experiments, prompts, and teaching artifacts traceable over multiple years.

## Core Names

- **Intelligent Requirements Engineering (IRE)**: The umbrella research and teaching program.
- **ChatREQ**: The core knowledge-driven multi-agent requirements engineering system.
- **IRE-Bench**: The benchmark infrastructure for requirements engineering tasks and evaluation protocols.
- **IRE-Datasets**: The dataset collection for dialogues, requirements, SRS documents, graphs, conflicts, mappings, and executable tasks.
- **IRE-Knowledge**: The knowledge infrastructure for standards, cases, ontologies, retrieval, embeddings, and knowledge graphs.
- **IRE-Evaluation**: The shared evaluation framework for metrics, scripts, result analysis, plots, and paper tables.

## Directory Names

Use the standardized repository directories:

- `docs`
- `papers`
- `benchmark`
- `knowledge`
- `system/chatreq`
- `groups/G{number}-{short-module}`
- `ai-resources`

## Dataset Names

Use the pattern:

`ire-dataset-{domain}-{task}-{version}`

Examples:

- `ire-dataset-campus-elicitation-v1`
- `ire-dataset-iot-conflicts-v1`
- `ire-dataset-webapp-architecture-mapping-v1`

## Figures

Use:

`fig-{paper-or-module}-{short-topic}.pdf`

Examples:

- `fig-chatreq-overview.pdf`
- `fig-reqgraph-traceability.pdf`
- `fig-envreq-context-injection.pdf`

## Tables

Use:

`tab-{paper-or-module}-{short-topic}.tex`

Examples:

- `tab-chatreq-main-results.tex`
- `tab-reqreview-conflict-types.tex`
- `tab-feasreq-resource-constraints.tex`

## Experiments

Use:

`exp-{module}-{task}-{dataset}-{version}`

Examples:

- `exp-chatclarify-questioning-campus-v1`
- `exp-reqreview-conflict-srs-v1`
- `exp-archreq-mapping-webapp-v1`

## Paper Files

Use lowercase kebab-case for draft folders and descriptive filenames:

- `chatreq-sigconf-2026/`
- `chatclarify-icse-style/`
- `reqgraph-ase-style/`
- `main.tex`
- `sections/introduction.tex`
- `refs/references.bib`

## Student Groups

Use:

`G{number}-{short-module-name}`

Examples:

- `G1-requirement-elicitation`
- `G4-conflict-detection`
- `G8-executable-requirements`

## Benchmarks

Use:

`benchmark-{task}-{version}`

Examples:

- `benchmark-clarification-v1`
- `benchmark-conflict-detection-v1`
- `benchmark-architecture-alignment-v1`

## Prompts

Use:

`prompt-{agent-role}-{task}-{version}.md`

Examples:

- `prompt-analyst-clarification-v1.md`
- `prompt-architect-feasibility-v1.md`
- `prompt-reviewer-conflict-checking-v1.md`
