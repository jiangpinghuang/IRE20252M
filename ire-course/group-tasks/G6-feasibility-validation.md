# G6: Feasibility Validation

## Group Name

G6 Feasibility Validation

## Research Theme

Feasibility-aware requirement validation under resource and deployment constraints.

## Suggested Paper Title

FeasREQ: Feasibility-Aware Requirement Validation under Resource and Deployment Constraints

## Research Motivation

Requirements can be clear and complete while still being infeasible because of budget, schedule, infrastructure, technical dependencies, legal constraints, or deployment environments. Feasibility validation should happen before architecture and implementation decisions become costly.

## Research Questions

- RQ1: Can knowledge-grounded feasibility validation identify infeasible requirements earlier?
- RQ2: Which constraint types most often drive infeasibility?
- RQ3: Can feasibility explanations help stakeholders revise requirements?

## System Module

FeasREQ module for constraint extraction, feasibility assessment, evidence retrieval, risk explanation, and revision recommendation.

## Knowledge Requirements

- Resource constraints.
- Deployment constraints.
- Platform and technology limitations.
- Regulatory or organizational constraints.
- Historical feasibility cases.

## Dataset Requirements

- Requirements labeled feasible, infeasible, or uncertain.
- Constraint evidence.
- Revision examples.
- Domain-specific feasibility cases.

## Baselines

- Single-prompt feasibility judgment.
- Checklist-based feasibility review.
- Retrieval-only feasibility baseline.
- Rule-based constraint checker.

## Evaluation Metrics

- Feasibility classification accuracy.
- Precision and recall for infeasible requirements.
- Evidence relevance.
- Revision usefulness.
- Human agreement.
- Downstream reduction in infeasible architecture decisions.

## Suggested Experiments

- Compare feasibility validation with and without retrieved evidence.
- Evaluate by constraint category.
- Test revision recommendation quality.
- Measure downstream architecture alignment effects.

## Threats to Validity

- Feasibility depends on local organizational assumptions.
- Labels may change as technology and resources change.
- Evidence retrieval can miss implicit constraints.
- Dataset examples may underrepresent complex tradeoffs.

## Weekly Milestones

- Week 1: Define feasibility taxonomy.
- Week 2: Build labeled feasibility dataset.
- Week 3: Implement constraint extraction.
- Week 4: Implement evidence-grounded validation.
- Week 5: Run baseline and ablation experiments.
- Week 6: Evaluate revision recommendations.
- Week 7: Prepare results and case examples.
- Week 8: Finalize paper draft and artifacts.

## Final Deliverables

- FeasREQ module.
- Feasibility dataset and schema.
- Evaluation results.
- Revision examples.
- ACM-style paper draft.

## Suggested Figures

- Feasibility validation pipeline.
- Constraint taxonomy.
- Example evidence-grounded feasibility explanation.

## Suggested Tables

- Feasibility dataset statistics.
- Validation accuracy by constraint type.
- Ablation study.

## Potential Target Venues

ICSE, ASE, FSE, RE, TOSEM, TSE.

