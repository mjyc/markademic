# Markademic

A pipeline for writing an academic paper using markdown; it convert *.md to *.tex to *.pdf in npm pkg.

## Getting started

1. Install [pdflatex](https://www.tug.org/applications/pdftex/)
2. Run `npm install`
3. Run `npm run build` and open `tex/paper.pdf`
4. Or run `npm run watch`, open `tex/paper.pdf`, and edit `draft.md` and `paper.pdf` will be updated on-the-fly
    * **IMPORTANT!** Your PDF viewer should support automatic-refresh; for OSX, I recommend using [Skim](https://skim-app.sourceforge.io) and [enable "Sync"](https://skim-app.sourceforge.io/manual/SkimHelp_39.html)
