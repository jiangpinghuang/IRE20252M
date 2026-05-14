# Contributing

This repository is a research and teaching workspace. Contributions should improve one or more of the following asset classes: papers, systems, datasets, knowledge bases, benchmarks, or evaluation artifacts.

## Working Principles

- Keep contributions traceable to a research question, system module, dataset need, or evaluation requirement.
- Preserve the provided ACM template under `docs/acmart-primary/`; do not modify it unless the project explicitly decides to upgrade the template.
- Keep experiments reproducible with scripts, configuration files, input data references, and result summaries.
- Separate raw data, processed data, annotations, benchmark tasks, and paper-ready artifacts.
- Use concise commit messages that describe the research asset being changed.

## Branch and Pull Request Workflow

1. Create a topic branch for a task, group module, dataset update, or paper revision.
2. Make small commits that can be reviewed independently.
3. Document any new dataset, metric, baseline, prompt, or experiment protocol.
4. Open a pull request with motivation, changed files, validation steps, and known limitations.
5. Address advisor and peer review comments before merging.

## Paper Contributions

Paper work should use the ACM SIGCONF skeletons under `ire-papers/` and the provided `docs/acmart-primary/` template. Contributions should make research claims explicit and connect them to research questions, baselines, ablations, evaluation metrics, threats to validity, and reproducibility material.

## Dataset Contributions

Dataset additions should include source, license or usage constraints, schema, annotation rules, quality checks, and intended benchmark use. Do not commit sensitive, private, or personally identifiable information.

## System Contributions

System changes should include tests or validation notes proportional to the risk of the change. Multi-agent behavior, knowledge retrieval, and evaluation code should be configurable and documented.

