# Paper Strategy

IRE follows an ACM-first paper strategy. Conference papers should be written in ACM SIGCONF style and designed so that strong modules can later be extended into TOSEM/TSE journal submissions.

## ACM SIGCONF First

All conference-style papers should use the provided ACM template in `docs/acmart-primary/`. The reusable skeleton under `ire-papers/group-papers/template-paper/` references that template and preserves the ACM metadata structure.

Do not create a separate LaTeX template from scratch. When the ACM template must be upgraded, upgrade `docs/acmart-primary/` deliberately and document the change.

## ICSE/ASE/FSE Writing Style

Software engineering conference papers should emphasize:

- Clear problem motivation grounded in RE practice.
- Explicit research questions.
- Method details sufficient for reproduction.
- Strong baselines.
- Ablation studies.
- Benchmark-oriented evaluation.
- Practical significance, not only model performance.
- Threats to internal, external, construct, and conclusion validity.
- Availability of code, data, prompts, and scripts when possible.

## Conference-to-Journal Extension

Conference papers should be structured so they can grow into TOSEM/TSE submissions. Journal extensions should add:

- Stronger theory and broader related work.
- More datasets and domains.
- More complete system description.
- Additional baselines and ablations.
- Longitudinal or human study evidence.
- Deeper validity analysis.
- Reproducibility package maturity.

## Subgroup Papers and the Master Paper

Each subgroup paper should contribute a focused module to the master ChatREQ paper:

- G1 contributes elicitation and dynamic questioning.
- G2 contributes environment-aware requirement generation.
- G3 contributes requirement graph structuring and traceability.
- G4 contributes conflict detection and consistency checking.
- G5 contributes adaptive human-in-the-loop control.
- G6 contributes feasibility validation.
- G7 contributes requirement-to-architecture alignment.
- G8 contributes executable requirements and task planning.

The master TOSEM/TSE paper should integrate these modules into an end-to-end ChatREQ system with shared datasets, knowledge assets, benchmark tasks, and evaluation protocols.

## Reproducibility Expectations

Every paper should identify:

- Code version.
- Dataset version.
- Prompt version.
- Knowledge base version.
- Experiment configuration.
- Baselines and parameters.
- Evaluation scripts.
- Random seeds where applicable.
- Hardware and model access assumptions where applicable.

## Benchmark Expectations

Benchmark claims should specify:

- Task input and output.
- Data source and split.
- Ground truth or annotation procedure.
- Metrics.
- Baselines.
- Human evaluation protocol when needed.
- Known limitations.

## Evaluation Rigor

IRE papers should avoid unsupported claims. Strong evaluations should combine automatic metrics, human review, qualitative error analysis, ablation studies, and downstream task utility when possible.

