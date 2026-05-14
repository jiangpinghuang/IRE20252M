# Research Assets

IRE is organized around five asset classes that must evolve together: paper assets, system assets, data assets, knowledge assets, and evaluation assets.

## 1. Paper Assets

Paper assets include drafts, outlines, LaTeX skeletons, figures, tables, algorithms, related work summaries, experiment descriptions, threat analyses, and reproducibility appendices.

Paper assets should make research claims explicit through:

- Research questions.
- Motivating examples.
- Method definitions.
- Baselines.
- Ablation studies.
- Evaluation metrics.
- Threats to validity.
- Reproducibility material.

## 2. System Assets

System assets include ChatREQ agents, workflows, prompts, knowledge routing logic, artifact schemas, configurations, examples, and tests.

System assets should be modular enough to support comparison across:

- Agent roles.
- Retrieval strategies.
- Knowledge representations.
- Human-in-the-loop policies.
- End-to-end workflows.
- Baseline implementations.

## 3. Data Assets

Data assets include raw and processed requirements, clarification dialogues, SRS documents, requirement graphs, conflict cases, architecture mappings, environment descriptions, and executable task plans.

Data assets should include provenance, schema, annotation guidelines, quality checks, and intended benchmark usage.

## 4. Knowledge Assets

Knowledge assets include standards, historical SRS examples, domain knowledge, ontologies, knowledge graphs, vector stores, expert knowledge, interview logs, and deployment constraints.

Knowledge assets should be structured so that ChatREQ agents can retrieve relevant evidence and route it to the appropriate role.

## 5. Evaluation Assets

Evaluation assets include benchmark task definitions, baselines, metrics, experiment configurations, scripts, result analysis, plots, and LaTeX tables.

Evaluation assets should support repeatable comparison and paper-ready reporting.

## Why Assets Must Co-Evolve

The project should avoid isolated artifacts. A paper claim should be connected to a system capability, a dataset, a knowledge source, and an evaluation protocol. Likewise, a system module should be tied to research questions, benchmark tasks, and expected paper contributions.

Co-evolution ensures that:

- System development supports publishable research.
- Datasets expose realistic and reusable task complexity.
- Knowledge sources improve agent behavior in measurable ways.
- Evaluation results are reproducible.
- Future student cohorts can extend prior work instead of restarting from scratch.

