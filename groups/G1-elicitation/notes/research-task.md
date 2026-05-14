# G1: Requirement Elicitation

## Group Name

G1 Requirement Elicitation

## Research Theme

Missing-information-aware requirement elicitation through dynamic multi-round questioning.

## Suggested Paper Title

ChatClarify: Missing-Information-Aware Requirement Elicitation via Dynamic Multi-Round Questioning

## Research Motivation

Early requirements are often incomplete, ambiguous, and underspecified. Analysts need to identify missing stakeholders, goals, constraints, assumptions, acceptance criteria, and environment conditions before producing reliable requirements.

## Research Questions

- RQ1: Can dynamic multi-round questioning improve requirement completeness compared with single-pass generation?
- RQ2: Which missing-information categories are most important for downstream requirement quality?
- RQ3: How many clarification rounds are needed before quality gains saturate?

## System Module

ChatClarify agent module for missing-information detection, question generation, answer integration, and clarification stopping decisions.

## Knowledge Requirements

- Missing-information taxonomy.
- Requirement elicitation patterns.
- Domain-specific stakeholder and constraint knowledge.
- Examples of high-quality clarification dialogues.

## Dataset Requirements

- Project ideas with intentionally missing information.
- Multi-round clarification dialogues.
- Gold or expert-reviewed completed requirement sets.
- Labels for missing information categories.

## Baselines

- Single-prompt LLM requirement generation.
- Static checklist-based elicitation.
- Retrieval-augmented single-agent elicitation.
- Human-authored analyst questions where available.

## Evaluation Metrics

- Requirement completeness.
- Question relevance.
- Redundancy rate.
- Information gain per round.
- Human correction effort.
- Downstream conflict and ambiguity reduction.

## Suggested Experiments

- Compare zero-round, one-round, and multi-round elicitation.
- Ablate missing-information taxonomy.
- Compare generic versus domain-aware questions.
- Measure quality under different stopping policies.

## Threats to Validity

- Expert judgments may vary across annotators.
- Synthetic missing information may not reflect real projects.
- LLM behavior may change across model versions.
- Completeness metrics may not capture all stakeholder needs.

## Weekly Milestones

- Week 1: Define missing-information taxonomy and task scope.
- Week 2: Build initial dataset examples and annotation rules.
- Week 3: Implement question generation prompt or agent workflow.
- Week 4: Implement answer integration and stopping policy.
- Week 5: Run baseline comparisons.
- Week 6: Analyze errors and revise dataset.
- Week 7: Produce figures, tables, and draft results.
- Week 8: Submit final module package and paper draft.

## Final Deliverables

- ChatClarify module specification.
- Dataset sample and annotation guidelines.
- Baseline and ablation results.
- Paper draft in ACM style.
- Reproducibility checklist.

## Suggested Figures

- Multi-round clarification workflow.
- Missing-information taxonomy.
- Completeness gain by clarification round.

## Suggested Tables

- Dataset statistics.
- Baseline comparison.
- Ablation results by missing-information category.

## Potential Target Venues

ICSE, ASE, FSE, RE, TOSEM, TSE.

