# AGENTS.md

Guidelines for OpenCode agents working in this repository.

## Overview
This repository contains the LaTeX documentation project for **Bounty Run EC**, a game design document for the "Desarrollo de Videojuegos - 30817" course (EPN template style).

## Build & Compilation Commands
- **Compile PDF document**: `latexmk -pdf main.tex`
- **Clean build files**: `latexmk -c` (or `latexmk -C` for full clean including PDF)

## Repository Structure
- `main.tex`: Main LaTeX entrypoint compiling indices, bibliography, and sections.
- `Documento/`: Document sections (`Documento.tex`, `Help.tex`, and `Secciones/` containing granular `.tex` chapters like gameplay, schedule, budget, risk analysis, etc.).
- `STY/`: Custom style definitions (`INICIO.sty`, `slashbox.sty`).
- `Imagenes/`: Image assets and logos.
- `Bibliografia.bib`: Bibliography source file (BibTeX).

## Environment & Toolchain
- Requires a full LaTeX distribution (`texlive-full`) and `latexmk`.
- Configured via `.devcontainer/devcontainer.json`.
