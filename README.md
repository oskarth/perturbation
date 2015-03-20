
# TODOs

- better organization in general
- when ODE, main part, more text is needed - why outer/inner appears
- tihkonov padeapprox a bit (if write about approx anyway)
- outer soln no exact diff (?) sister to inner which is connected to start t=0

- borghans chosen timescales a bit, no repeat but nice to have an example of how you do it, otherwise math lacking
- Jag har inte åsikt egentligen.  På något sätt vore det trevligt att jfr approx med exakt

skalfaktorer:
Jag menar så enkelt t=a\tau typ vad är a?  Det är inte självklart en
student här skulle veta om det.

grapha; Jag funderar på varför den se så platt ut  Jag menar bara en enkel kurva



# Low prio TODOs

- Define y in (23)
- Cite method for dominant balance after (24)
- y is treated as a constant (~) after (24) (but it's a fn of O(1))

## Misc
v1 explanation of singular perturbation theory, using TQSSA as an example.

First part - What is singular perturbation theory?
Second part - How to use it to justify TQSSA?

Is this for real or something else?

4/3, 22/4, 27/5, 17/6, 19/8

To generate references, do a multi-pass.

```
pdflatex latex_source_code.tex
bibtex latex_source_code.aux
pdflatex latex_source_code.tex
pdflatex latex_source_code.tex
```
