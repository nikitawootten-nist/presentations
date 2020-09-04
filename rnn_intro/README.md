# RNN Introduction Presentation - 9/1/2020
This presentation walks users through the basics of recurrent neural networks, including:
* Basic dataset exploration
* Simple RNN, LSTM and GRU architecture, and how to train them with tensorflow/keras
* Interpreting model results
* New advances with recurrent neural networks

## Requirements
In order to run this notebook, your python environment *must* have the following packages (in addition to `jupyter-notebook`):
```
tensorflow
pandas
numpy
sklearn
matplotlib
```

For easy installation, I have exported my [conda](https://docs.conda.io/en/latest/) environment to `environment.yaml`. It can be installed to your local system with the following command (provided that you have anaconda installed on your system):
```
$ conda env create -f environment.yaml
```

### Dataset

In order to download the dataset automatically see slide `Introducting our benchmark dataset`), you must install the `kaggle` command and add your credentials. You can skip that step and download the dataset manually from [here](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

### Presenting

In order to present a jupyter notebook, you must follow [these](https://www.blog.pythonlibrary.org/2018/09/25/creating-presentations-with-jupyter-notebook/) steps to install and enable `RISE`. Additionally, this presentation makes use of the [splitcell](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/splitcell/readme.html) extension, which must be installed in order for split slides to render correctly.

*Note: these extensions are not required to use the notebook, only to view it as a presentation*

## Changelog
* 09/04/2020: This readme was created, along with some adjustments to the notebook:
    - made dataset reading its own cell, for people that skip the kaggle download step
    - trimmed tokenizer index output
    - removed "todo" section
* 09/03/2020: Github repository created, presentation uploaded
* 09/01/2020: First showing of
* 08/30/2020: Initial draft
* 08/17/2020: Began working on this presentation