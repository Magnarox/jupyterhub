# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
ARG JUPYTERHUB_VERSION
FROM jupyterhub/jupyterhub:$JUPYTERHUB_VERSION

# Install dockerspawner, oauth, postgres
RUN /opt/conda/bin/pip install --no-cache-dir \
        oauthenticator==0.8.* \
        dockerspawner==0.9.*

# Copy the JupyterHub configuration in the container
COPY jupyterhub_config.py .
