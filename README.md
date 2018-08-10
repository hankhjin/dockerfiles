# Collection of my DockerFiles

* `DockerFile_myconda`
    - Build on [continuumio/anaconda3:latest](https://hub.docker.com/r/continuumio/anaconda3/)
    - Installs `build-essential`, `gcc`, `vim` from Debian repository
    - Installs `nlopt`, `jupyter_contrib_nbextensions` from conda-forge
    - Creates a `sudo group` user `docker`
    - Jupyter connection password is `docker`
