# Kaggle Cactus AI :cactus:

```bash
conda env remove -n tf
conda create -n tf python=3.8 cudatoolkit=11
conda activate tf
conda install matplotlib plotly pandas jupyter scipy
pip install tensorflow tensorboard tensor-dash
pip install -U tensorboard-plugin-profile
```

## Download data

```bash
mkdir data
cd data
# curl -o aerial-cactus-identification.zip https://www.kaggle.com/c/aerial-cactus-identification/data
unzip aerial-cactus-identification.zip
unzip test.zip
unzip train.zip
cd ..
```
