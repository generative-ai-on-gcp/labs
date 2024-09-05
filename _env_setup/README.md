# Setting up environment

## 1. Create a virtual environment

``` bash
ENV_NAME=genai-gcp
conda create -n $ENV_NAME python=3.10 ipykernel
conda activate $ENV_NAME
python -m ipykernel install --user --name=$ENV_NAME
```


## 2
``` bash
pip install -r requirements.txt
```