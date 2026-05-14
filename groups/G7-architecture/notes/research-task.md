# G7: Requirement-to-Architecture Alignment

## Group Name

G7 Requirement-to-Architecture Alignment

## Research Theme

Aligning software requirements with architecture design through knowledge-guided mapping.

## Suggested Paper Title

ArchREQ: Aligning Software Requirements with Architecture Design through Knowledge-Guided Mapping

## Research Motivation

Requirements often fail to connect clearly to architectural components, design decisions, quality attributes, and tradeoffs. This weakens traceability and makes it hard to assess whether architecture satisfies stakeholder needs.

## Research Questions

- RQ1: Can knowledge-guided mapping improve requirement-to-architecture traceability?
- RQ2: Which requirement types are hardest to align with architecture?
- RQ3: Can architecture mapping expose missing or conflicting design decisions?

## System Module

ArchREQ module for extracting architectural concerns, mapping requirements to components and decisions, explaining alignment, and detecting unmapped requirements.

## Knowledge Requirements

- Architecture style knowledge.
- Design pattern knowledge.
- Quality attribute scenarios.
- Architecture decision records.
- Requirement graph context.

## Dataset Requirements

- Requirements paired with architecture descriptions.
- Requirement-to-component mappings.
- Architecture decision records.
- Quality attribute scenarios.
- Unmapped or weakly mapped requirement examples.

## Baselines

- Text similarity mapping.
- Single-prompt LLM mapping.
- Retrieval-augmented mapping without graph context.
- Manual mapping reference where available.

## Evaluation Metrics

- Mapping precision, recall, and F1.
- Explanation quality.
- Unmapped requirement detection.
- Architecture coverage.
- Quality attribute alignment.
- Downstream design review usefulness.

## Suggested Experiments

- Compare mapping methods on multiple project domains.
- Ablate architecture knowledge and requirement graph context.
- Evaluate quality attribute mapping separately.
- Conduct case study on architecture review.

## Threats to Validity

- Architecture ground truth may be incomplete.
- Mapping quality may depend on architecture description detail.
- Quality attribute interpretation can be subjective.
- Results may differ for large industrial systems.

## Weekly Milestones

- Week 1: Define mapping schema.
- Week 2: Collect requirement and architecture examples.
- Week 3: Build baseline mapping methods.
- Week 4: Implement knowledge-guided mapping.
- Week 5: Run evaluation and ablations.
- Week 6: Analyze unmapped and weakly mapped requirements.
- Week 7: Prepare architecture figures and tables.
- Week 8: Finalize deliverables.

## Final Deliverables

- ArchREQ module.
- Mapping dataset and schema.
- Evaluation and ablation results.
- Case study examples.
- ACM-style paper draft.

## Suggested Figures

- Requirement-to-architecture mapping workflow.
- Example requirement-to-component traceability graph.
- Architecture alignment error taxonomy.

## Suggested Tables

- Mapping dataset statistics.
- Baseline comparison.
- Quality attribute alignment results.

## Potential Target Venues

ICSE, ASE, FSE, RE, ECSA, TOSEM, TSE.

