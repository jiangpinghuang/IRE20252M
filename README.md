# Intelligent Requirements Engineering (IRE)

Intelligent Requirements Engineering (IRE) is a long-term research and teaching workspace for building infrastructure, datasets, benchmarks, and papers around intelligent requirements engineering.

The core system in this repository is **ChatREQ**, a knowledge-driven multi-agent system for end-to-end requirements engineering.

## Vision

IRE aims to build a durable research infrastructure for intelligent requirements engineering. The project treats requirements engineering as a full lifecycle problem that connects elicitation, clarification, structuring, validation, traceability, architecture alignment, and executable planning.

The repository is organized to continuously accumulate five classes of research assets:

- **Paper assets**: ACM SIGCONF papers, journal outlines, figures, tables, algorithms, related work, and reusable writing guidelines.
- **System assets**: ChatREQ agents, workflows, prompts, configurations, implementation artifacts, and tests.
- **Data assets**: raw and processed datasets for requirement dialogues, SRS documents, requirement graphs, conflict cases, and architecture mappings.
- **Knowledge assets**: standards, domain knowledge, historical SRS cases, ontologies, knowledge graphs, embeddings, and retrieval pipelines.
- **Evaluation assets**: benchmark tasks, baselines, metrics, scripts, experiment configurations, result analysis, plots, and LaTeX tables.

## Research Themes

- Knowledge-driven requirements engineering
- Multi-agent collaboration
- Human-in-the-loop systems
- End-to-end requirements engineering
- Intelligent requirement elicitation
- Requirement graph reasoning
- Requirement validation
- Requirement-to-architecture alignment
- Executable requirements

## Repository Overview

| Path | Purpose |
| --- | --- |
| `docs/` | Project vision, roadmap, naming rules, research asset policy, collaboration workflow, and paper strategy. |
| `docs/acmart-primary/` | Provided ACM `acmart` template. This is the only paper-writing foundation for ACM papers in this workspace. |
| `chatreq/` | Core ChatREQ system assets, including agents, knowledge, workflows, prompts, configurations, datasets, evaluation, examples, and tests. |
| `ire-course/` | Graduate course materials, group tasks, weekly reports, project guidelines, paper templates, and final reports. |
| `ire-papers/` | Master paper, group papers, reusable ACM skeletons, related work, writing guidelines, and paper assets. |
| `ire-datasets/` | Dataset construction, annotation guidelines, schemas, examples, and benchmark-ready data categories. |
| `ire-bench/` | Benchmark tasks, baselines, metrics, scripts, configs, results, and LaTeX-ready tables. |
| `ire-knowledge/` | Standards, SRS cases, domain knowledge, retrieval, embeddings, ontologies, and knowledge extraction pipelines. |
| `ire-evaluation/` | Shared evaluation metrics, scripts, experiment configs, analysis notebooks, plots, and paper tables. |

## Student Collaboration Workflow

Students work in groups aligned with research modules. Each group is expected to maintain weekly progress notes, update datasets and benchmark artifacts, produce reproducible experiments, and contribute paper-ready figures, tables, and text.

The standard workflow is:

1. Select a group task and confirm the research scope.
2. Maintain weekly reports under `ire-course/weekly-reports/`.
3. Implement system modules under `chatreq/` when needed.
4. Add or update dataset artifacts under `ire-datasets/`.
5. Register benchmark tasks and evaluation protocols under `ire-bench/`.
6. Produce figures, tables, and paper drafts under `ire-papers/`.
7. Review work through GitHub issues, pull requests, and advisor feedback.

## Research Roadmap

The first phase focuses on ChatREQ v1, graduate course organization, eight group research modules, benchmark v1, and ICSE/ASE/FSE-style conference papers. Later phases focus on reusable datasets, stronger knowledge-driven collaboration, a stable open-source platform, a public benchmark, and TOSEM/TSE-style journal extensions.

See [docs/roadmap.md](docs/roadmap.md) for the detailed plan.

## Long-Term Goal

The long-term goal is to support ICSE/ASE/FSE/TOSEM/TSE-level intelligent requirements engineering research through a coherent infrastructure where papers, systems, datasets, knowledge bases, and evaluation assets co-evolve.

