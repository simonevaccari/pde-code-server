# Processor Development Environment (PDE) Container image

The Processor Development Environment provides a rich, interactive environment in which processing algorithms and services are developed, tested, debugged and ultimately packaged so that they can be deployed to the platform and published via the marketplace.

This repository contains a Dockerfile to build a container that exposes [Code Server](https://github.com/cdr/code-server) within a the ApplicationHub.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/) installed on your machine.
- [ApplicationHub](https://eoepca.github.io/application-hub-context/) installed and configured.

### Building the Docker Image

To build the Docker image, run the following command:

```bash
docker build -t eoepca/pde-code-server .
```
