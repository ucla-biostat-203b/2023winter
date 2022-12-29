# docker build . -t huazhou/ucla_biostat_203b_2023w
# docker run -it -p 8888:8888 -v /Users/huazhou/Documents/Box\ Sync/MIMIC/mimic-iv-1.0:/srv/mimic-iv huazhou/lange_symposium_workshop_2022
# docker-compose up

# https://rocker-project.org/images/versioned/rstudio.html
# ubuntu: 22.04 (jammy), R: 4.2.2, Python: 3.10
FROM rocker/geospatial:4.2.2

RUN /rocker_scripts/install_jupyter.sh

COPY install_extra_pkgs.sh /rocker_scripts/install_extra_pkgs.sh

RUN /rocker_scripts/install_extra_pkgs.sh