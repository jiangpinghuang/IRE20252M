# G2: Environment-Aware Requirements

## Group Name

G2 Environment-Aware Requirements

## Research Theme

Environment-aware requirements generation with contextual knowledge injection.

## Suggested Paper Title

EnvREQ: Environment-Aware Requirements Generation with Contextual Knowledge Injection

## Research Motivation

Requirements are shaped by deployment environments, physical context, organizational constraints, external systems, regulations, user devices, and operational conditions. Ignoring environment context can lead to infeasible or incomplete requirements.

## Research Questions

- RQ1: Does environment knowledge improve requirement relevance and feasibility?
- RQ2: Which environment dimensions contribute most to requirement quality?
- RQ3: Can contextual knowledge injection reduce missing assumptions?

## System Module

EnvREQ module for environment modeling, contextual retrieval, requirement enrichment, and environment-risk analysis.

## Knowledge Requirements

- Environment context taxonomy.
- Domain constraints.
- Deployment platform information.
- External system and interface knowledge.
- Operational and regulatory constraints.

## Dataset Requirements

- Project ideas with environment descriptions.
- Requirement sets with and without environment constraints.
- Labels for environment assumptions.
- Cases where environment mismatch causes requirement problems.

## Baselines

- Requirement generation without environment context.
- Prompt-only environment checklist.
- Retrieval-augmented generation without role-specific routing.
- Manual environment analysis where available.

## Evaluation Metrics

- Environment coverage.
- Requirement feasibility.
- Assumption detection.
- Context relevance.
- Reduction in environment-related defects.
- Human review effort.

## Suggested Experiments

- Compare no-context, generic-context, and knowledge-injected generation.
- Ablate environment dimensions such as users, devices, external systems, and deployment constraints.
- Evaluate cross-domain transfer.
- Conduct error analysis on infeasible generated requirements.

## Threats to Validity

- Environment realism may depend on dataset quality.
- Domain experts may disagree on feasibility.
- Context injection can introduce irrelevant constraints.
- Results may not generalize across domains.

## Weekly Milestones

- Week 1: Define environment taxonomy.
- Week 2: Collect and normalize environment examples.
- Week 3: Build contextual knowledge injection workflow.
- Week 4: Generate baseline and EnvREQ outputs.
- Week 5: Annotate feasibility and environment coverage.
- Week 6: Run ablations and error analysis.
- Week 7: Prepare paper figures and tables.
- Week 8: Finalize module and draft.

## Final Deliverables

- EnvREQ module specification.
- Environment dataset and schema.
- Evaluation results and ablation study.
- ACM-style paper draft.
- Reproducibility package.

## Suggested Figures

- Contextual knowledge injection pipeline.
- Environment taxonomy.
- Example of environment-driven requirement revision.

## Suggested Tables

- Environment category statistics.
- Baseline comparison.
- Ablation results by environment dimension.

## Potential Target Venues

ICSE, ASE, FSE, RE, TOSEM, TSE.

