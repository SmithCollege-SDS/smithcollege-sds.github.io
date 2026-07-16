smithcollege-sds.github.io
================

<!-- badges: start -->
[![website](https://github.com/SmithCollege-SDS/smithcollege-sds.github.io/actions/workflows/quarto.yaml/badge.svg)](https://github.com/SmithCollege-SDS/smithcollege-sds.github.io/actions/workflows/quarto.yaml)
<!-- badges: end -->

SDS content for the web not managed by college relations, available at
<https://smithcollege-sds.github.io/>

### In order to edit this website:

1.  The layout/style is based on `_quarto.yml`
2.  The contents are based on all `.qmd/.Rmd` files

### In order to preview this website locally:
To check your work locally, you'll need to install all of the R packages.  The most up-to-date list of these is in `quarto.yaml`

1. open the R Console in your editor (e.g. Positron) and run:
```
install.packages(c(
  "remotes", "tidyverse", "DT", "emoji", "ggrepel", 
  "googlesheets4", "here", "htmltools", "kableExtra", 
  "knitr", "ical", "lubridate", "mosaic", "janitor"
))
```

2. in the terminal, run `quarto preview`

### In order to build this website:

1.  Just make a commit, the build will be triggered automatically by
    GitHub Actions.

The resulting `gh-pages` branch will contain all `.html` files