# PyTorch


## Introduction

This is a first introduction to getting to grips with pyTorch, it was presented at "les midis de la bidouille" at Inria Bordeaux.
It is inspired by many tutorials including that of IBM for Harvard. 

This tutorial is divided into two parts:

   1. The creation of 1D and 2D tensors (multidimensional matrices
      containing elements of the same data type in PyTorch),
      access their content / index them, operations between tensors
      (addition...).

   2. Calculate the derivative of a tensor.


## Informations to run the code
To Run the notebooks you have to install torch and other libraries. 
A way to do that is to create a conda environment to download the needed libraries and then run the notebook.

## Download conda


Install : https://conda.io/projects/conda/en/latest/user-guide/install/linux.html#install-linux-silent

## Install the provided conda environnement 

```shell=bash
conda env create f pytorch_p37.yml
conda activate pytorch_p37
```

## Or create yourself and install the needed libraries

```shell=bash
conda update conda
conda env create -n pytorch_p37 python=3.6
conda activate pytorch_p37
conda install numpy
conda install pandas
conda install matplotlib
conda install scikit-learn
conda install tensorflow
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch
jupyter notebook
```
