# ChatREQ: A Knowledge-Driven Multi-Agent System for End-to-End Requirements Engineering

This outline targets a TOSEM/TSE-style journal paper that integrates the ChatREQ system, IRE-Bench, IRE-Datasets, IRE-Knowledge, and IRE-Evaluation into a coherent research contribution.

## Contributions

- A knowledge-driven multi-agent architecture for end-to-end requirements engineering.
- A modular workflow connecting elicitation, environment awareness, requirement graph construction, consistency checking, human-in-the-loop review, feasibility validation, architecture alignment, and executable task planning.
- A reusable knowledge layer for standards, historical SRS documents, domain knowledge, constraints, ontologies, embeddings, and requirement graphs.
- A benchmark and dataset infrastructure for evaluating intelligent requirements engineering systems.
- An empirical evaluation with baselines, ablations, user or case studies, and reproducibility artifacts.

## 1. Introduction

- Motivate requirements engineering as a high-impact software engineering activity.
- Explain why modern projects need intelligent support across the full RE lifecycle.
- Identify limitations of traditional RE tools and single-LLM approaches.
- Present ChatREQ as a knowledge-driven multi-agent system.
- Summarize the research questions, evaluation design, and contributions.

Candidate research questions:

- RQ1: How effectively can ChatREQ improve completeness and consistency of requirements artifacts?
- RQ2: How much does knowledge-driven multi-agent collaboration improve over single-agent and single-prompt baselines?
- RQ3: How do different knowledge sources affect elicitation, validation, traceability, and architecture alignment?
- RQ4: How much human effort can adaptive human-in-the-loop control reduce while preserving quality?
- RQ5: How useful are ChatREQ artifacts for downstream architecture, testing, and task planning?

## 2. Background and Motivation

- Requirements elicitation, analysis, validation, traceability, and management.
- Multi-agent systems in software engineering.
- Retrieval-augmented and knowledge-grounded LLM systems.
- Benchmarking challenges in requirements engineering.
- Motivating example that runs through the paper.

## 3. Research Challenges

- Missing, ambiguous, and conflicting stakeholder information.
- Domain and environment context gaps.
- Traceability across heterogeneous artifacts.
- Long-horizon multi-step RE workflows.
- Reliable human-in-the-loop intervention.
- Evaluation beyond surface text quality.
- Reproducibility under evolving LLM and retrieval components.

## 4. ChatREQ Overview

- System architecture and major components.
- Agent roles and responsibilities.
- Shared artifact model.
- Workflow orchestration.
- Human review points.
- Interfaces to datasets, knowledge bases, and benchmarks.

Suggested figure: ChatREQ end-to-end architecture.

## 5. Knowledge Layer

- Knowledge sources: standards, SRS cases, domain knowledge, deployment constraints, interview logs, repositories, and architecture records.
- Knowledge extraction pipelines.
- Knowledge representation through text chunks, schemas, embeddings, ontologies, and graphs.
- Retrieval and role-specific knowledge routing.
- Knowledge provenance, versioning, and lifecycle.

Suggested ablations:

- No retrieval.
- Generic retrieval only.
- Role-specific retrieval.
- Knowledge graph only.
- Vector retrieval plus knowledge graph.

## 6. Multi-Agent Collaboration Layer

- Agent roles: elicitation analyst, environment analyst, graph builder, consistency reviewer, human-effort controller, feasibility analyst, architect, task planner, and meta-reviewer.
- Collaboration protocols for proposal, critique, revision, and escalation.
- Artifact handoff and version tracking.
- Conflict resolution and uncertainty handling.

Suggested figure: Agent collaboration protocol.

## 7. End-to-End Requirements Engineering Workflow

- Input project idea or stakeholder request.
- Missing information detection and clarification.
- Requirement generation and structuring.
- Requirement graph construction.
- Conflict and consistency review.
- Feasibility validation.
- Architecture mapping.
- Executable task generation.
- Human review and final SRS packaging.

Suggested table: Workflow stages, inputs, outputs, agents, knowledge, and metrics.

## 8. Benchmark and Dataset Infrastructure

- IRE-Datasets categories and schemas.
- IRE-Bench task definitions.
- Annotation and quality control.
- Data splits and benchmark protocols.
- Baseline definitions.
- Reproducibility package.

Benchmark ideas:

- Clarification question quality.
- Environment-aware requirement generation.
- Requirement graph construction accuracy.
- Conflict detection and explanation quality.
- Human-in-the-loop effort reduction.
- Feasibility judgment accuracy.
- Requirement-to-architecture mapping.
- Requirement-to-task transformation.

## 9. Experimental Setup

- Datasets and domains.
- Baselines.
- Model, retrieval, and agent configurations.
- Metrics and statistical analysis.
- Human evaluation protocol.
- Implementation details.

Candidate baselines:

- Manual analyst reference.
- Single-prompt LLM.
- Chain-of-thought single-agent LLM.
- Retrieval-augmented single-agent LLM.
- Rule-based RE checker.
- Graph-only method.
- ChatREQ without knowledge.
- ChatREQ without multi-agent critique.
- ChatREQ without human-in-the-loop adaptation.

## 10. Results and Analysis

- Main quantitative results by task.
- Per-domain and per-requirement-type breakdowns.
- Ablation studies.
- Error analysis.
- Cost and latency analysis.
- Robustness to incomplete or noisy input.

Evaluation metrics:

- Completeness.
- Consistency.
- Conflict detection precision, recall, and F1.
- Traceability link precision, recall, and graph quality.
- Feasibility judgment accuracy.
- Human effort measured by intervention count, time, and correction volume.
- Downstream utility for architecture, testing, and planning.
- Reproducibility and stability across runs.

## 11. User Study / Case Study

- Study design with students, analysts, or domain participants.
- Tasks, training, and materials.
- Measurements: quality, time, workload, trust, correction effort, and perceived usefulness.
- Qualitative feedback.
- Case study on one or more realistic software projects.

## 12. Discussion

- What knowledge-driven multi-agent collaboration adds.
- Where ChatREQ succeeds and fails.
- Practical deployment implications.
- Cost, governance, and human oversight.
- Lessons for intelligent software engineering systems.

## 13. Threats to Validity

- Internal validity: implementation defects, prompt effects, model instability, annotation bias.
- Construct validity: metric alignment with real RE quality.
- External validity: domain coverage, participant representativeness, project scale.
- Conclusion validity: statistical power, multiple comparisons, noisy human ratings.
- Reproducibility threats: evolving LLM APIs, dataset licensing, environment differences.

## 14. Related Work

- Requirements engineering automation.
- LLMs for software engineering.
- Multi-agent software engineering systems.
- Retrieval-augmented generation and knowledge graphs.
- Human-in-the-loop software engineering.
- RE benchmarks, datasets, and empirical methods.
- Requirement traceability, validation, and architecture alignment.

## 15. Conclusion

- Restate the need for end-to-end intelligent requirements engineering.
- Summarize ChatREQ, IRE-Bench, and empirical findings.
- Highlight implications for research infrastructure and teaching.
- Identify next steps toward open-source release and public benchmark adoption.

## Reproducibility Strategy

- Release code, prompts, configuration files, benchmark tasks, evaluation scripts, and processed datasets where allowed.
- Version all datasets, knowledge bases, prompts, models, and experiment configurations.
- Provide scripts that regenerate metrics, figures, and LaTeX tables.
- Document model access assumptions and fallback baselines.
- Preserve raw human evaluation materials and anonymized annotation records when permitted.

## Future Extensions

- Conference-to-journal expansion from group modules.
- Cross-domain benchmark release.
- Longitudinal use in graduate courses.
- Deeper requirement-to-code and requirement-to-task workflows.
- Lifelong learning from project history and post-deployment feedback.

