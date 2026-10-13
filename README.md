# Bioinformatics Project Scaffold
This repo helps scaffold new bioinformatics projects according to my preferred way of working. The main idea is to have a `quarto` manuscript project to write the paper easily, and several `md`, `qmd` or `ipynb` that describe analyses and steps (like a lab notebook). I also have taken a liking to separating each step of the project into separate numbered folders, and while the scaffold does not reflect that (yet), it is the way I like to do it.

## Getting started

To create a new project, use
```sh
copier copy --trust gh:Matt-BF/bioinformatics-project-scaffold my-new-project
```
Change `my-new-project` to the name you want for your project.

You can also use copier without installing, although you still need `uv` or `pixi`

With `uv`
```sh
uvx copier copy --trust gh:Matt-BF/bioinformatics-project-scaffold my-new-project
```

With `pixi`
```sh
pixi exec copier copy --trust gh:Matt-BF/bioinformatics-project-scaffold my-new-project
```

## Scaffolding
The template prompts to init the project with either `pixi` or `uv`, and goes through a series of questions to start the project. Many of them have default answers, so you can just press enter to keep going

## Structure
- `manuscript.qmd` — the manuscript (Quarto manuscript project; render with `quarto render`)
- `data/` - input data
- `figures/` - output figures
- `scripts/` - general scripts
- `binaries/` - program binaries
- `containers/` - apptainer/docker containers
- `references.bib` - bibliography
