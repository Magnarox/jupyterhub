# Jupyterhub

Build notebook image :

    cd notebook
    docker build -t jupyterhub-user:latest . 

Create network :
    
    docker network create jupyterhub-network