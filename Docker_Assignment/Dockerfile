# Docker inheritance
FROM risserlin/bcb420-base-image
# Install packages
RUN R -e 'BiocManager::install(c("DESeq2"))'
RUN R -e "install.packages(c('pheatmap'),dependencies=TRUE, repos='http://cran.rstudio.com/')"