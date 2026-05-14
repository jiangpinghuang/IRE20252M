# G5: Adaptive Human-in-the-Loop

## Group Name

G5 Adaptive Human-in-the-Loop

## Research Theme

Adaptive human-in-the-loop control for reducing human effort in intelligent requirements engineering.

## Suggested Paper Title

AdaptiveHITL-REQ: Reducing Human Effort in Intelligent Requirements Engineering

## Research Motivation

Human expertise is essential for requirements engineering, but not every system decision needs the same level of review. Adaptive human-in-the-loop policies can route uncertain, high-risk, or high-impact cases to humans while allowing low-risk steps to proceed automatically.

## Research Questions

- RQ1: Can adaptive intervention policies reduce human effort without reducing requirement quality?
- RQ2: Which uncertainty and risk signals best predict when human review is needed?
- RQ3: How do different escalation strategies affect user trust and correction effort?

## System Module

AdaptiveHITL-REQ module for uncertainty estimation, risk scoring, intervention selection, feedback capture, and review policy adaptation.

## Knowledge Requirements

- Human review criteria.
- Risk categories.
- Uncertainty indicators.
- Historical correction patterns.
- Task-specific quality thresholds.

## Dataset Requirements

- Agent outputs with human corrections.
- Intervention logs.
- Review decisions and outcomes.
- Quality labels before and after human feedback.

## Baselines

- Always-human review.
- Never-human review.
- Fixed-threshold review.
- Random review sampling.
- Single-agent self-confidence baseline.

## Evaluation Metrics

- Human effort reduction.
- Final artifact quality.
- Review precision.
- Missed critical issue rate.
- Correction volume.
- User trust and perceived workload.

## Suggested Experiments

- Compare adaptive policies with fixed policies.
- Ablate uncertainty signals.
- Simulate different reviewer availability levels.
- Conduct user study on review burden and trust.

## Threats to Validity

- Student reviewers may not represent professional analysts.
- Simulated effort may differ from real review cost.
- Trust measures may be subjective.
- Adaptive policies may overfit to dataset-specific error patterns.

## Weekly Milestones

- Week 1: Define intervention policy design.
- Week 2: Collect sample outputs and correction data.
- Week 3: Implement risk and uncertainty scoring.
- Week 4: Implement review routing workflow.
- Week 5: Run policy comparisons.
- Week 6: Conduct user or simulated review study.
- Week 7: Analyze effort-quality tradeoffs.
- Week 8: Finalize deliverables.

## Final Deliverables

- AdaptiveHITL-REQ module.
- Intervention dataset.
- Policy comparison results.
- User or simulation study report.
- ACM-style paper draft.

## Suggested Figures

- Adaptive human-in-the-loop workflow.
- Effort-quality tradeoff curve.
- Risk scoring model.

## Suggested Tables

- Intervention policy comparison.
- Human effort statistics.
- Missed issue analysis.

## Potential Target Venues

ICSE, ASE, FSE, CHI, RE, TOSEM, TSE.

