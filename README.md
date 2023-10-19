# CS7641_project_2

Author: Yu Feng
GID: yfeng40

The project can be clone from https://github.com/leonyufeng/CS7641_project_2
By commend `git clone https://github.com/leonyufeng/CS7641_project_2`

# 1. Getting data
The Mexican COVID Death classification can be downloaded at https://www.kaggle.com/datasets/meirnizri/covid19-dataset?resource=download. The Credit Score classification dataset can be download at https://www.kaggle.com/datasets/parisrohan/credit-score-classification .
The dataset is also included in the data folder. In case it’s not included due to uploading limit, please do download the data from the web links provided above. And put the two dataset css files into `data` folder with correct name `covid_death_dataset.csv`.

## 2.1 Environment setup
1) Install Anaconda or miniconda from
`https://docs.conda.io/en/latest/miniconda.html`

2) Create conda environment by
`conda create -n CS6741_RO python=3.8`
Then activate conda env by `conda activate CS6741_RO`
3) Then install libraries at project root by
`pip install -r requirements.txt`

Since the project only asked for analysis.pdf and RDADME.txt, Therefore, you can also install the python libraries by
`pip install pandas`
 `pip install scikit-learn`
`pip install matplotlib`
`pip install jupyter`
`pip install ipykernel`
`pip install mlrose-hiive`

There is a joblib library dependency issue for library mlrose-hiive, therefore also need to reinstall joblib as
`pip install -U joblib=1.2`

4) Add kernel to jupyter notebook by
`python -m ipykernel install --user --name CS6741_RO`

## 2.2 Open jupyter notebook
1) Open jupyter notebook case
Open jupyter notebook from terminal by
`jupyter notebook`
2) Change kernel from Jupyter Notebook Menu Kernel/Change Kernel to CS6741_RO

## 2.3 Run through the notebook
There are Four notebooks `ContinuousPeaks.ipynb`, `FlipFlop.ipynb`, `KColor.ipynb` and `NeuralNetworkOptimization.ipynb` for each case
You can simply use `run all` under menu `run` to run through each notebook. But be aware that, each notebook will run over 1-2 hours due to the size of the data. It will be especially slow for GA and MIMIC for each case.

## 2.4 Run results
The results can be find in notebook for each case.
