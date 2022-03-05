# Econometrics

Econometrics is the use of statistical methods using quantitative data to develop theories or test existing hypotheses in economics or finance. Econometrics relies on techniques such as regression models and null hypothesis testing. Econometrics can also be used to try to forecast future economic or financial trends.

## Installation
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/312FinTech/Econometrics/HEAD)
### Locally Using Conda
```
conda create --name 312fintechenv python=3.8.8 -y
conda activate 312fintechenv
conda install -c anaconda ipykernel -y
ipython kernel install --user --name=312fintechenv
pip install -r requirements.txt
conda install -c conda-forge prophet -y
```
