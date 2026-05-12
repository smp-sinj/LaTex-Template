# LaTeX Template (Overleaf + XeLaTeX)

This repository provides a report template intended to be used **on Overleaf** with the **XeLaTeX** compiler.  
It is set up so users can focus on writing content while keeping the structure and styling consistent.

## Purpose

Use this template to quickly prepare course/project reports with:
- a predefined title page,
- predefined formatting and notation helpers,
- bibliography support,
- multilingual labels (French/English) controlled from configuration.

## Intended workflow

The template is designed so editing is concentrated in only two places:

1. **`config.tex`** for metadata and report settings (language, title, authors, professors, etc.).
2. **`main.tex`** for the report body/content.

You typically should not need to modify the other files.

## How to use on Overleaf

1. Create a new Overleaf project and upload this repository.
2. In Overleaf settings, set the compiler to **XeLaTeX**.
3. Update `config.tex` with your report information.
4. Write your sections/content in `main.tex`.
5. Compile.

## Notes

- Keep your bibliography entries in `mybib.bib`.
- Figures should be placed in the `figures/` folder.
