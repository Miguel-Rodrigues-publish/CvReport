# index.html generation

```bash
Rscript -e 'rmarkdown::render("index.Rmd", (output_format="html_document"))'
cd ../WHO
./bin/analytics.sh ../WHO-site/index.html
cd ../WHO-site/
```
