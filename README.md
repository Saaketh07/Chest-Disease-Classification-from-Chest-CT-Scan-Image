# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## how to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml


## Mlflow dagshub connection uri

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/Saaketh07/MLflowm-Experiment-demo.mlflow \
MLFLOW_TRACKING_USERNAME=Saaketh07 \
MLFLOW_TRACKING_PASSWORD=2403d9842f5cdfdb08b6b4d1f298c66f30af34b2 \
python script.py
```


## RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/Saaketh07/MLflowm-Experiment-demo.mlflow 

export MLFLOW_TRACKING_USERNAME=Saaketh07

export MLFLOW_TRACKING_PASSWORD=2403d9842f5cdfdb08b6b4d1f298c66f30af34b2
```