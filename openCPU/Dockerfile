FROM opencpu/base:latest

RUN R -e 'install.packages("remotes", repos = "https://cloud.r-project.org")'
RUN R -e 'remotes::install_github("inowas/kwb.heatsine.opencpu@dev")'
