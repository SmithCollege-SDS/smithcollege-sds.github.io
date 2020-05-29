sds-www
================

SDS content for the web not managed by college relations, available at
<https://smithcollege-sds.github.io/sds-www/>

In order to edit this website:

1.  The layout/style is based on `www/_site.yml`
2.  The contents is based on all `.Rmd` files in the `www/` folder

In order to build this website:

1.  If you haven’t already
      - Install the `sds` package following these
        [instructions](https://github.com/SmithCollege-SDS/sds)
      - Install the `bannerweb` package
2.  Using Terminal/command line
      - Navigate to `www/`
      - Run `make`

The resulting `docs/` folder will contain all `.html` files
