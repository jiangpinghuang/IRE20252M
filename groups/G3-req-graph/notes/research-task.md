# G3: Requirement Graph

## Group Name

G3 Requirement Graph

## Research Theme

Graph-based requirement structuring and traceability reasoning.

## Suggested Paper Title

ReqGraph: Graph-Based Requirement Structuring and Traceability Reasoning

## Research Motivation

Requirements are connected through goals, dependencies, conflicts, refinements, constraints, rationale, and architecture links. Flat requirement lists make these relationships difficult to inspect, validate, and reuse.

## Research Questions

- RQ1: Can graph-based structuring improve traceability and review quality?
- RQ2: Which node and edge types are most useful for requirement reasoning?
- RQ3: How accurately can agents construct requirement graphs from informal inputs and SRS text?

## System Module

ReqGraph module for extracting requirement entities, constructing typed edges, detecting graph inconsistencies, and supporting traceability queries.

## Knowledge Requirements

- Requirement graph schema.
- Traceability relation taxonomy.
- Domain entity vocabulary.
- Examples of requirement-to-goal, requirement-to-constraint, and requirement-to-architecture links.

## Dataset Requirements

- Requirement lists and SRS documents.
- Annotated graph nodes and edges.
- Traceability ground truth.
- Graph query tasks and expected answers.

## Baselines

- Flat requirement list representation.
- Rule-based entity and relation extraction.
- Single-agent LLM graph extraction.
- Retrieval-augmented extraction without graph validation.

## Evaluation Metrics

- Node extraction precision, recall, and F1.
- Edge extraction precision, recall, and F1.
- Traceability query accuracy.
- Graph consistency.
- Review time reduction.
- Downstream architecture mapping utility.

## Suggested Experiments

- Compare graph extraction methods across domains.
- Ablate edge types.
- Evaluate graph validation rules.
- Measure downstream gains for conflict detection and architecture alignment.

## Threats to Validity

- Graph annotations can be subjective.
- Metrics may overemphasize local edge accuracy over usefulness.
- Small datasets may not capture large project complexity.
- Graph schemas may need adaptation across domains.

## Weekly Milestones

- Week 1: Define graph schema and relation taxonomy.
- Week 2: Annotate initial graph examples.
- Week 3: Implement graph extraction workflow.
- Week 4: Implement graph validation and query examples.
- Week 5: Run baseline comparisons.
- Week 6: Analyze graph errors.
- Week 7: Prepare graph visualizations and tables.
- Week 8: Finalize deliverables.

## Final Deliverables

- ReqGraph schema.
- Annotated graph dataset.
- Extraction and validation results.
- ACM-style paper draft.
- Graph visualization examples.

## Suggested Figures

- Requirement graph schema.
- End-to-end graph construction workflow.
- Case study graph visualization.

## Suggested Tables

- Node and edge type statistics.
- Extraction accuracy.
- Traceability query results.

## Potential Target Venues

ICSE, ASE, FSE, RE, TOSEM, TSE.

