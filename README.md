# Cross-View Association of Identical Parts Across Non-Overlapping 3D Scans: Identifiability, Shift Ambiguity and Evaluation

Bachelor's thesis in Artificial Intelligence and Data Analytics, University of Trieste, academic year 2025/2026.

- Candidate: Sabrina Ciccolo
- Supervisor: Prof. Alejandro Rodriguez Garcia

The code, the experiments and the results behind the thesis are in [pairbench](https://github.com/SabrinaCiccolo/pairbench).

## Contents

- `main.pdf`: the compiled thesis
- `main.tex`, `bibThesis.bib`, `fig/`: the LaTeX source
- `presentation/discussion.pptx`: the slides of the thesis defence

## Data

The real scans used in this thesis were provided by beanTech, the company that developed the vision software of the rig. The raw point clouds are proprietary and are not included in this repository or in pairbench, so the figures and slides show only views derived from them.

## Building

The thesis uses `biblatex` with the `biber` backend:

```
latexmk -pdf main.tex
```
