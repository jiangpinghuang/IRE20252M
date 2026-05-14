# IRE-Knowledge

IRE-Knowledge stores knowledge assets used by ChatREQ agents and benchmark tasks.

## Knowledge Sources

Initial knowledge sources include:

- Requirements engineering standards.
- Historical SRS documents.
- Expert knowledge.
- Domain knowledge.
- Deployment constraints.
- Interview logs.
- Software repositories.
- Architecture decision records.
- Testing and validation artifacts.

## Standards

Standards and guidelines should be tracked with source, version, scope, and usage constraints. Examples include SRS structure guidance, safety standards, domain regulations, and organizational engineering rules.

## Knowledge Extraction

Extraction pipelines should convert unstructured and semi-structured sources into reusable representations such as concepts, constraints, requirement patterns, conflict rules, traceability links, and rationale statements.

## Knowledge Representation

IRE-Knowledge should support multiple representations:

- Text chunks for retrieval.
- Structured schemas for requirements and constraints.
- Knowledge graph nodes and edges.
- Ontologies for domain concepts and relationships.
- Embeddings for semantic search.

## Vector Retrieval

Vector retrieval should support role-specific grounding. Retrieval metadata should include source, version, domain, task, and confidence where possible.

## Knowledge Graph

The knowledge graph should model stakeholders, goals, requirements, constraints, conflicts, dependencies, architecture elements, validation artifacts, and executable tasks.

## Role-Specific Knowledge Routing

ChatREQ agents should receive knowledge relevant to their responsibilities. For example, an architect agent needs architectural constraints, a reviewer agent needs conflict rules, and an elicitation agent needs missing-information patterns.

## Lifelong Knowledge Updates

Knowledge assets should support continuous updates from new datasets, user feedback, paper findings, benchmark failures, and system revisions. Updates should preserve provenance and version history.

