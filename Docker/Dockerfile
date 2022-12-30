# Sample usage: 
#
# docker build . -t huazhou/ucla_biostat_203b_2023w
# docker-compose up
# docker image push huazhou/ucla_biostat_203b_2023w
#
# https://rocker-project.org/images/versioned/rstudio.html
# ubuntu: 22.04 (jammy), R: 4.2.2, Python: 3.10
FROM rocker/geospatial:4.2.2

RUN /rocker_scripts/install_jupyter.sh

COPY install_extra_pkgs.sh /rocker_scripts/install_extra_pkgs.sh

RUN /rocker_scripts/install_extra_pkgs.sh