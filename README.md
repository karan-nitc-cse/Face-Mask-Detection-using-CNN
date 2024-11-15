# Face-Mask-Detection-using-CNN

## Overview
This Jupyter Notebook, train_model.ipynb, is designed to train a machine learning model. It includes steps for data preprocessing, model selection, training, and evaluation.

## Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Data](#data)
4. [Model Training](#model-training)
5. [Results](#results)

## Installation
To run this notebook on Linux, you will need to install Anaconda, which includes Python, Jupyter Notebook, and many useful libraries.


### Step 1: Download Anaconda
1. Open your terminal.
2. Download the Anaconda installer using wget (or use your browser):

```bash
wget https://repo.anaconda.com/archive/Anaconda3-2023.07-Linux-x86_64.sh
```

### Step 2: Install Anaconda
1. Run the installer script in terminal.
bash
bash Anaconda3-2023.07-Linux-x86_64.sh


### Step 3: Verify Installation
bash
conda --version


### Step 4: Install all Requirements for this project
From requirements.txt file by running bash command in terminal
```bash
pip install -r requirements.txt
```

### Step 5: Launch Jupyter Notebook
You can find the Jupyter Notebook file used for this project [here](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/36364148/3637a198-4dec-40e6-9fb1-e501e5261507/train_model.ipynb).
```bash
jupyter notebook
```


### Step 6: If do not works then use below commands for linux(Ubuntu)
```bash
eval "$(/home/linux/anaconda3/bin/conda shell.bash hook)"
```
# And second as this command
```bash
anaconda-navigator
```

## Usage
Do the model Training. Save the model and utilise it for Detecting Facemask.

## Data

Utilise Kaggle Data Set for Training the model.
You can find the Data set from [here](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset).


## Model Training
Use the Python script train_model.ipynb to train the model and save this model
as mask_detector_model.h5 and utilise it for Facemask Detection.

## Results
Save the results in the seperate Directory result.
##
