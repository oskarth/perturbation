## TODO

- fix punctuation in equations. , and . in right places.
- check other submitted to see missing.

## Misc

To generate references, do a multi-pass.

```
pdflatex latex_source_code.tex
bibtex latex_source_code.aux
pdflatex latex_source_code.tex
pdflatex latex_source_code.tex
```
