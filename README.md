# thesis-report

Thesis reports and similar short documents

First move to the `src`directory and lauch R

```bash
cd src
radian
```
Then run the knit command adapting to your input file and output directory

```R
rmarkdown::render('report.rmd', output_dir = '../docs/report/report', output_format = 'all', knit_root_dir = getwd())
```

- report observable at https://commons-research.github.io/thesis-report/report/report/report.html

