# Vision

Intelligent Requirements Engineering (IRE) is a long-term research program for building knowledge-driven, multi-agent, human-centered infrastructure for end-to-end requirements engineering.

## Why Traditional Requirements Engineering Is Limited

Traditional requirements engineering relies heavily on interviews, workshops, manual document analysis, and expert review. These practices remain valuable, but they are difficult to scale when projects involve many stakeholders, changing environments, distributed teams, and complex software ecosystems.

Common limitations include:

- Missing or ambiguous stakeholder intent.
- Weak traceability between goals, requirements, constraints, architecture, and tasks.
- Delayed detection of conflicts, infeasibility, and missing assumptions.
- Expensive manual validation and review.
- Limited reuse of historical project knowledge.
- Weak feedback loops between requirements, design, implementation, deployment, and operation.

## Why Single-LLM Approaches Are Not Enough

Large language models can summarize, rewrite, classify, and generate requirements, but a single prompt-response workflow is not a sufficient foundation for rigorous requirements engineering.

Single-LLM approaches often struggle with:

- Persistent project memory and knowledge reuse.
- Role-specific reasoning across stakeholders, analysts, architects, testers, and domain experts.
- Explicit conflict detection and evidence tracking.
- Structured traceability and graph reasoning.
- Reproducible evaluation across benchmarks and baselines.
- Controlled human-in-the-loop intervention.
- Long-running workflows that require state, accountability, and revision.

IRE treats LLMs as components inside a broader knowledge-driven system rather than as a complete requirements engineering process by themselves.

## Why Intelligent Requirements Engineering Matters

Requirements remain one of the highest-leverage artifacts in software engineering. Poor requirements can lead to wrong systems, costly rework, architectural mismatch, unsafe behavior, and failed stakeholder alignment. Intelligent requirements engineering aims to improve the quality, speed, traceability, and evidence base of requirements work.

The project focuses on systems that can help analysts:

- Elicit missing information through targeted clarification.
- Transform informal ideas into structured requirements.
- Build requirement graphs and traceability links.
- Detect conflicts, incompleteness, and infeasibility.
- Align requirements with architecture and implementation tasks.
- Reuse knowledge from standards, historical SRS documents, and software repositories.

## Why Knowledge-Driven Multi-Agent Collaboration Is Needed

Requirements engineering is naturally multi-role. Stakeholders provide goals and constraints; analysts structure and negotiate requirements; architects assess feasibility; testers reason about validation; project managers consider resources and delivery; domain experts supply contextual knowledge.

A knowledge-driven multi-agent system can assign specialized responsibilities to agents while grounding their work in shared knowledge. In ChatREQ, agents should be able to:

- Retrieve role-specific knowledge.
- Debate, critique, and revise requirements.
- Escalate uncertain cases to humans.
- Maintain traceability between claims and evidence.
- Coordinate across elicitation, analysis, validation, and planning.

This architecture enables more explicit reasoning than a single monolithic assistant.

## Why End-to-End RE Automation Matters

Many existing tools address isolated tasks such as requirement classification or ambiguity detection. Real projects need connected workflows. An elicited requirement should connect to constraints, rationale, conflicts, architecture decisions, test ideas, and executable tasks.

End-to-end automation matters because it enables:

- Continuous refinement from idea to validated requirement.
- Traceability across lifecycle artifacts.
- Integrated quality checks instead of late-stage review only.
- Reuse of intermediate artifacts in evaluation and papers.
- Better alignment between research prototypes and practical RE work.

## Why Benchmark Construction Matters

Research progress requires benchmarks that make claims measurable. IRE-Bench should support controlled comparison of agents, prompts, retrieval strategies, graph methods, human-in-the-loop policies, and end-to-end workflows.

Benchmark construction matters because it provides:

- Shared tasks for repeated evaluation.
- Baselines for fair comparison.
- Metrics for completeness, consistency, traceability, feasibility, human effort, and downstream utility.
- Reproducible experimental protocols.
- Evidence for ICSE/ASE/FSE/TOSEM/TSE-level claims.

## Why Papers, Systems, and Datasets Must Co-Evolve

Papers without reusable systems and datasets are difficult to validate. Systems without papers often lack clear research claims. Datasets without systems and evaluation protocols often fail to drive progress.

IRE therefore requires co-evolution:

- Papers define research questions and claims.
- Systems operationalize methods.
- Datasets expose realistic task complexity.
- Knowledge assets ground agent behavior.
- Evaluation assets test whether the claims hold.

Every major project artifact should be reusable by future students and future papers.

## Future Directions

### Cognition

IRE will explore cognitive models of requirements understanding, including uncertainty, intent inference, memory, critique, negotiation, and explanation.

### Embodied Systems

Future requirements engineering will increasingly involve cyber-physical and embodied systems. IRE will study how environment context, sensors, deployment constraints, and operational feedback shape requirements.

### Requirement-to-Code

The project will investigate how structured requirements can support code generation, code review, test generation, and implementation traceability.

### Requirement-to-Task

IRE will study how requirements can be transformed into executable tasks for planning, validation, implementation, and monitoring.

### Lifelong Requirement Learning

ChatREQ should continuously learn from prior projects, feedback, revisions, evaluations, and failures while preserving data provenance and human oversight.

