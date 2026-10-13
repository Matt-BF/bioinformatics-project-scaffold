# Bioinformatics Project Scaffold
This repo helps scaffold new bioinformatics projects according to my preferred way of working. The main idea is to have a `quarto` manuscript project to write the paper easily, and several `md`, `qmd` or `ipynb` that describe analyses and steps (like a lab notebook). I also have taken a liking to separating each step of the project into separate numbered folders, and while the scaffold does not reflect that (yet), it is the way I like to do it.

## Scaffolding
The template prompts to init the project with either `pixi` or `uv`

## Structure
- `manuscript.qmd` — the manuscript (Quarto manuscript project; render with `quarto render`)
- `data/` - input data
- `figures/` - output figures
- `scripts/` - general scripts
- `binaries/` - program binaries
- `containers/` - apptainer/docker containers
- `references.bib` - bibliography
