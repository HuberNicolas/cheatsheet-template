# TODO

Open tasks for the template.

## 1. Build

- [x] Compile the 2020 version with TeX Live 2026 (pdfLaTeX, compiles with overfull heading boxes)
- [x] Build with latexmk (`.latexmkrc`) and in GitHub Actions; attach the PDF to releases
- [ ] Check the first workflow run on GitHub after the push

## 2. Template (v2)

- [x] Move layout and macros into `cheatsheet.sty` with a `columns` option
- [x] Heading boxes via KOMA's `\sectionlinesformat`, sized to the column (no overfull boxes)
- [x] Replace `commath` with `mathtools` paired delimiters; drop unused packages (`amscd`, `empheq`, `esint`, `tikz`, `color`, duplicate `inputenc`)
- [x] Fix content errors: union/intersection swapped, `\setminus` is set difference, `\log`, "Binomialkoeffizient"
- [ ] Optional: an English example next to the German one

## 3. License and release

- [x] Add the GPLv3 text the README referred to
- [ ] Decide whether GPLv3 stays or the template moves to MIT like `minimalistic-cv-template`
- [ ] Tag the 2020 state as `v1.0.0` and the update as `v2.0.0`; the workflow attaches the PDF
