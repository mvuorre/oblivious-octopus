Submission to prejudice modelling competition

- Our materials: <https://github.com/mvuorre/oblivious-octopus>
- Competition website: <https://hehmanlab.org/competition>
- Competition OSF repo: <https://osf.io/7wz3y/?view_only=>

## Reproduce

We conducted our analyses as a Quarto R notebook whose R environment is managed by renv. To reproduce, render the Quarto project. Optimally also ensure you have the same R environment as us. To be exact,

```bash
git clone https://github.com/mvuorre/oblivious-octopus.git
cd oblivious-octopus
Rscript -e "renv::restore()"
quarto render index.qmd
```
