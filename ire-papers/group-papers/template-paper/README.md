# ACM SIGCONF Template Paper

This folder is the reusable paper skeleton for IRE group papers.

## Template Policy

This skeleton uses the provided ACM template in `docs/acmart-primary/` as its only LaTeX foundation. It does not copy or modify the original ACM files.

The key references are:

- Document class: `../../../docs/acmart-primary/acmart.cls`
- Bibliography style: `../../../docs/acmart-primary/ACM-Reference-Format.bst`

## Structure

| Path | Purpose |
| --- | --- |
| `main.tex` | ACM SIGCONF entry point with metadata, abstract, CCS, keywords, sections, and bibliography. |
| `sections/` | Modular paper sections following ICSE/ASE/FSE-style structure. |
| `figures/` | Paper figures. |
| `tables/` | Paper tables. |
| `algorithms/` | Algorithm pseudocode or method fragments. |
| `refs/references.bib` | Paper bibliography. |

## Compile

From this directory:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

The skeleton is set up for ACM SIGCONF review-style software engineering papers. For TOSEM/TSE-style extension, reuse the section files and adapt the ACM document class option according to the target venue requirements.

## Writing Expectations

Each paper should include:

- Research questions.
- Baselines.
- Ablation studies.
- Threats to validity.
- Reproducibility notes.
- Benchmark-oriented evaluation.

