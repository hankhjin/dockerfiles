# Collection of my Dockerfiles

* `Dockerfile.myconda`
    - Builds on [continuumio/anaconda3:latest](https://hub.docker.com/r/continuumio/anaconda3/)
    - Installs `build-essential`, `gcc`, `vim` from Debian repository
    - Installs `nlopt`, `jupyter_contrib_nbextensions` from conda-forge
    - Creates a default `sudo group` user `docker`
    - Jupyter connection password is `docker`

* `Dockerfile.mylatex`
    - Builds on `debian:latest`
    - Downloads and installs `texlive 2018` with scheme-full
    - Creates a default `sudo group` user `docker`
