# kubernetes_and_docker_samples

## Prerequisites:

A running docker engine.

## Samples:

### A datascience notebook server (jupyter):

To start the jupyter server from samples/datascience_notebook open a terminal and:

    cd samples/datascience_notebook

    docker compose -f docker-compose.yml up

Your notebooks will be stored in samples/datascience_notebook/notebooks subfolder by default.

Use Control-C to stop the server
