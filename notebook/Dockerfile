FROM jupyter/r-notebook:latest
ARG JUPYTERHUB_VERSION=0.9.3
RUN pip install --no-cache \
    jupyterhub==$JUPYTERHUB_VERSION

USER root
RUN apt-get update && apt-get install iputils-ping -y
USER jovyan