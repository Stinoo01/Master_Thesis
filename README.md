# Multilayer graph modeling of gene expression data
This repository contains the code for the master thesis 2024/2025 in Data Science at Sapienza, University of Rome

## Model Description

## System Requirements

### Operating system 

For the model it was used a Windows (Ubuntu 18.04) operating systems.

Chromoformer was trained using a server with 40 Intel(R) Xeon(R) Silver 4210R @ 2.40GHz CPUs, 128GB RAM and two GeForce RTX 3090 GPUs. The training procedure internally utilizes 8 cores (workers) and memory (RAM) footprint was <8GB throughout the training loop. GPU memory usage was ~10GB.

According to the statistics above, we provide the optimal hardware requirements as follows:

CPU requirement: 8+ cores, 2.40+ GHz per core
GPU requirement: 16+ GB GPU

### Python packages

The model was trained and tested using Python 3.12.3 with the following packages versions:

numpy: 1.26.4
pandas: 2.2.2
matplotlib: 3.9.2
seaborn: 0.13.2
sklearn: 1.5.1
xgboost: 3.0.0
lightgbm: 4.6.0
torch: 2.7.0+cpu
statsmodels: 0.14.2
mygene: 3.2.2

## Replicatig the experiment

## Training from scratch 
