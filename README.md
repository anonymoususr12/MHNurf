# Multifaceted Hierarchical Performance Bug ReportIdentification for Deep Learning Projects

<!-- ABOUT THE PROJECT -->
## About The Project
This online appendix is supplementary to the paper entitled "Multifaceted Hierarchical Performance Bug ReportIdentification for Deep Learning Projects".. It contains the raw results, code for the proposed approach, and Colab script to replicate our experiments.

This README file describes the structure of the provided files (Raw data, source code and results). as well as information on the content of this repository.

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#Data">Data</a></li>
    <li><a href="#Model">Model</a></li>
    <li><a href="#Statistical Analysis">Statistical Analysis</a></li>
    <li><a href="#Result">Result</a></li>
  </ol>
</details>

## Getting Started

### Installation


```
!git clone https://github.com/anonymoususr12/MHPurf
```

The easiest way to execute the codes for the proposed approach is to download the .ipyb script you need and run it in Google Colaboratory, where you can execute the Python code or R code in your broswer.

## Data
### Experiment dataset
In `/data` directory, you can find the raw data used in our experiments in `tensorFlow.csv`, `pytorch.csv`, `keras.csv` , `incubator-mxnet.csv` and `caffe.csv`. These files will be loaded automatically in each model script.

### Embedding
GloVe embedding pre-trained word vectors is stored in `/data/embedding` directory. But word2vec embedding for LSTM&CNN models is not uploaded due to GitHub file size limit. It can be downloaded from https://wikipedia2vec.github.io/wikipedia2vec/pretrained/.

### Create your own dataset
We also provide a tool which allows you to create your own dataset by executing the code in `data/features_collecting.ipynb`.

## Model

## Statistical Analysis

## Result
