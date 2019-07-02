#!/usr/bin/env Rscript

all: www

www: index.Rmd  _site.yml include/after_body.html include/smith.css awards.Rmd mu_sigma_rho.Rmd
	Rscript -e "rmarkdown::render_site();"
#	sed -i "s/’/'/g" $@
#	sed -i 's/“/"/g' $@
#	sed -i 's/”/"/g' $@
#	sed -i 's/—/\&mdash;/g' $@
#	sed -i 's/–/\&ndash;/g' $@

clean:
	Rscript -e "rmarkdown::clean_site();"

