# end_end_ML_project_MLflow

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py
10. Update the dvc.yaml if possible; this is not in project




# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/hossain-sanowar/end_end_ML_project_MLflow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n image-GPU python=3.9 -y
```

```bash
conda activate image-GPU
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/hossain-sanowar/end_end_ML_project_MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=hossain-sanowar \
MLFLOW_TRACKING_PASSWORD=80f69da54c9358d5dfccf54eb23dd5d647095a17 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/hossain-sanowar/end_end_ML_project_MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=hossain-sanowar 

export MLFLOW_TRACKING_PASSWORD=80f69da54c9358d5dfccf54eb23dd5d647095a17

```
```cmd

set MLFLOW_TRACKING_URI=https://dagshub.com/hossain-sanowar/end_end_ML_project_MLflow.mlflow

set MLFLOW_TRACKING_USERNAME=hossain-sanowar 

set MLFLOW_TRACKING_PASSWORD=80f69da54c9358d5dfccf54eb23dd5d647095a17

```