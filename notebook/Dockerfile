FROM jupyter/r-notebook:latest
ARG JUPYTERHUB_VERSION=0.9.3
RUN pip install --no-cache \
    jupyterhub==$JUPYTERHUB_VERSION

# Add R libraries here
RUN conda install r-sampling -y

USER jovyan