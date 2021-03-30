# Missing data in supervised ML

Datasets are almost never complete and this can introduce various biases to your analysis. Due to these biases, your supervised machine learning model can produce incorrect predictions. The goal of this post is to give you an idea of why some of the most common approaches for dealing with missing values often introduce some type of bias. At ODSC East 2021, I will describe the methods and techniques that can help you to arrive at an unbiased conclusion in the face of missing data.

## Prerequistes

Please run check_env.ipynb. It checks the versions of your python and some packages (like pandas, sklearn, xgboost). If the notebook returns all OK, you should be able to run missing_data_in_supervised_ML.ipynb without issues. If some FAILs are returned, you need to install/update those packages first. 

You can recreate the python environment using the env.yml conda environment file by running these two commands in the terminal:

`conda env create -n env -f env.yml`

`conda activate env`

You should be able to start jupyter-notebook now and run the check_env.ipynb.

## Description

`missing_data_in_supervised_ML.ipynb` is the main notebook, the slides of the presentation. The notebook is also available in pdf format for convenience.

`\data` contains the kaggle house price dataset and its description.

## Authors

Andras Zsom (andras_zsom@brown.edu).

## License

This project is licensed under the MIT License.
