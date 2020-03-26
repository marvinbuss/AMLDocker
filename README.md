![Docker](https://github.com/marvinbuss/aml-docker/workflows/Docker/badge.svg)

# Azure Machine Learning Docker Image

This Docker image is based on  the `python:3-slim` image and comes pre-installed with the [Azure Machine Learning SDK for Python](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py). The image is publicly available on Docker Hub: https://hub.docker.com/r/marvinbuss/aml-docker

# GitHub Actions for Azure Machine Learning

This image is used for several GitHub Actions for Azure Machine Learning:

- [aml-workspace](https://github.com/Azure/aml-workspace) - Connects to or creates a new workspace
- [aml-compute](https://github.com/Azure/aml-compute) - Connects to or creates a new compute target in Azure Machine Learning
- [aml-run](https://github.com/Azure/aml-run) - Submits a ScriptRun, an Estimator or a Pipeline to Azure Machine Learning
- [aml-registermodel](https://github.com/Azure/aml-registermodel) - Registers a model to Azure Machine Learning
- [aml-deploy](https://github.com/Azure/aml-deploy) - Deploys a model and creates an endpoint for the model

For more information, please visit the repositories of the respective action.
There are also templates available, which show you, how the end to end process looks like:

- [aml-template]() - Sample project, which uses all previously mentioned GitHub Actions
