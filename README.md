![Docker](https://github.com/marvinbuss/aml-docker/workflows/Docker/badge.svg)

# Azure Machine Learning Docker Image

This Docker image is based on  the `python:3-slim` image and comes pre-installed with the [Azure Machine Learning SDK for Python](https://docs.microsoft.com/en-us/python/api/overview/azure/ml/?view=azure-ml-py). The image is publicly available on Docker Hub: https://hub.docker.com/r/marvinbuss/aml-docker

## Docker Container Details

Python Version: 3.8.2
Python packages (v1.1.5.1):
```sh
adal==1.2.2
applicationinsights==0.11.9
attrs==19.3.0
azure-common==1.1.25
azure-core==1.4.0
azure-graphrbac==0.61.1
azure-identity==1.3.1
azure-mgmt-authorization==0.60.0
azure-mgmt-containerregistry==2.8.0
azure-mgmt-keyvault==2.2.0
azure-mgmt-resource==8.0.1
azure-mgmt-storage==9.0.0
azureml-automl-core==1.1.5.1
azureml-core==1.1.5.7
azureml-dataprep==1.3.2
azureml-dataprep-native==14.1.0
azureml-pipeline==1.1.5
azureml-pipeline-core==1.1.5
azureml-pipeline-steps==1.1.5
azureml-sdk==1.1.5
azureml-telemetry==1.1.5.3
azureml-train==1.1.5
azureml-train-automl-client==1.1.5.2
azureml-train-core==1.1.5
azureml-train-restclients-hyperdrive==1.1.5
backports.tempfile==1.0
backports.weakref==1.0.post1
certifi==2020.4.5.1
cffi==1.14.0
chardet==3.0.4
cloudpickle==1.3.0
contextlib2==0.6.0.post1
cryptography==2.9.2
distro==1.5.0
docker==4.2.0
dotnetcore2==2.1.13
entrypoints==0.3
flake8==3.7.9
fusepy==3.0.1
idna==2.9
importlib-metadata==1.6.0
isodate==0.6.0
jeepney==0.4.3
jmespath==0.9.5
jsonpickle==1.4.1
jsonschema==3.2.0
mccabe==0.6.1
msal==1.2.0
msal-extensions==0.1.3
msrest==0.6.13
msrestazure==0.6.3
ndg-httpsclient==0.5.1
oauthlib==3.1.0
pathspec==0.8.0
portalocker==1.7.0
pyasn1==0.4.8
pycodestyle==2.5.0
pycparser==2.20
pyflakes==2.1.1
PyJWT==1.7.1
pyOpenSSL==19.1.0
pyrsistent==0.16.0
python-dateutil==2.8.1
pytz==2019.3
requests==2.23.0
requests-oauthlib==1.3.0
ruamel.yaml==0.15.89
SecretStorage==3.1.2
six==1.14.0
urllib3==1.25.9
websocket-client==0.57.0
zipp==3.1.0
```

# GitHub Actions for Azure Machine Learning

This image is used for several GitHub Actions for Azure Machine Learning:

- [aml-workspace](https://github.com/Azure/aml-workspace) - Connects to or creates a new workspace
- [aml-compute](https://github.com/Azure/aml-compute) - Connects to or creates a new compute target in Azure Machine Learning
- [aml-run](https://github.com/Azure/aml-run) - Submits a ScriptRun, an Estimator or a Pipeline to Azure Machine Learning
- [aml-registermodel](https://github.com/Azure/aml-registermodel) - Registers a model to Azure Machine Learning
- [aml-deploy](https://github.com/Azure/aml-deploy) - Deploys a model and creates an endpoint for the model

For more information, please visit the repositories of the respective action.
There are also templates available, which show you, how the end to end process looks like:

1. Simple example: [ml-template-azure](https://github.com/machine-learning-apps/ml-template-azure) and
2. Comprehensive example: [aml-template](https://github.com/Azure/aml-template).
