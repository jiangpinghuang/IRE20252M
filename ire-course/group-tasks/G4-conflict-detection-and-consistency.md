# G4: Conflict Detection and Consistency

## Group Name

G4 Conflict Detection and Consistency

## Research Theme

Hybrid rule-LLM conflict detection for requirements consistency checking.

## Suggested Paper Title

ReqReview: Hybrid Rule-LLM Conflict Detection for Requirements Consistency Checking

## Research Motivation

Conflicting requirements can cause rework, failed validation, architectural mismatch, and stakeholder disagreement. Pure rule systems are precise but brittle, while LLM-only methods may be inconsistent and hard to audit.

## Research Questions

- RQ1: Can hybrid rule-LLM review improve conflict detection over rule-only and LLM-only baselines?
- RQ2: Which conflict types benefit most from rules, LLM reasoning, or graph context?
- RQ3: Can explanations improve human review efficiency?

## System Module

ReqReview module for conflict candidate generation, rule-based checking, LLM-based semantic review, explanation generation, and human confirmation.

## Knowledge Requirements

- Conflict taxonomy.
- Consistency rules.
- Domain constraints.
- Requirement graph context.
- Examples of confirmed and false-positive conflicts.

## Dataset Requirements

- Conflict cases with labels and explanations.
- Non-conflict requirement pairs.
- Requirement sets with injected and real conflicts.
- Human review annotations.

## Baselines

- Rule-only conflict checker.
- Single-prompt LLM conflict detector.
- Pairwise semantic similarity baseline.
- Requirement graph consistency baseline.

## Evaluation Metrics

- Precision, recall, and F1.
- False positive rate.
- Explanation usefulness.
- Conflict severity ranking.
- Human confirmation time.
- Consistency improvement after revision.

## Suggested Experiments

- Compare rule-only, LLM-only, and hybrid review.
- Evaluate performance by conflict type.
- Ablate graph context and domain knowledge.
- Test explanation quality with human reviewers.

## Threats to Validity

- Conflict labels may be subjective.
- Injected conflicts may be easier than real conflicts.
- Human evaluation may be affected by explanation style.
- Hybrid methods may depend on rule coverage.

## Weekly Milestones

- Week 1: Define conflict taxonomy.
- Week 2: Build labeled conflict dataset.
- Week 3: Implement rule-based checks.
- Week 4: Implement LLM semantic review.
- Week 5: Combine hybrid workflow and run baselines.
- Week 6: Evaluate explanations with reviewers.
- Week 7: Produce results and error analysis.
- Week 8: Finalize paper and artifacts.

## Final Deliverables

- ReqReview module.
- Conflict dataset and annotation guide.
- Hybrid evaluation results.
- Explanation examples.
- ACM-style paper draft.

## Suggested Figures

- Hybrid conflict detection workflow.
- Conflict taxonomy.
- Example conflict explanation.

## Suggested Tables

- Conflict dataset statistics.
- Detection results by conflict type.
- Explanation usefulness ratings.

## Potential Target Venues

ICSE, ASE, FSE, RE, TOSEM, TSE.

