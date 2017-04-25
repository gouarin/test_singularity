Bootstrap: docker
From: continuumio/miniconda

%runscript
    exec python "$@"

%post
    conda install -y mpi4py numpy
