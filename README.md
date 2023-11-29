# Code Server Docker Image

This repository contains a Dockerfile to build a container that exposes [Code Server](https://github.com/cdr/code-server) within a the ApplicationHub.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.
- [JupyterHub](https://jupyterhub.readthedocs.io/) installed and configured.

### Building the Docker Image

To build the Docker image, run the following command:

```bash
docker build -t jupyterhub-code-server .
```
