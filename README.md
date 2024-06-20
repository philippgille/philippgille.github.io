Philipp Gillé
=============

This repository contains the source and target files for my [personal website](https://philippgille.github.io).

The target file `index.html` is required here because GitHub differentiates between normal project "gh-pages" and "User Pages" and User Pages require their content to be located in the master branch.

Build
-----

1. Install [Pandoc](https://www.pandoc.org/)
2. Generate HTML: `pandoc resume_philipp-gille.md -f markdown -t html -s -c styles.css --metadata pagetitle="Résumé - Philipp Gillé" -o index.html`
3. Install a PDF rendering engine for Pandoc, e.g. *pdflatex* which is part of TeX Live via `sudo dnf install texlive`
4. Generate PDF: `pandoc resume_philipp-gille.md -f markdown -t pdf --metadata pagetitle="Résumé - Philipp Gillé" -o resume_philipp-gille.pdf`
