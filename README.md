# ProbExpan for the course "Experiment Design for Data Science" at TU Vienna

This repository contains the PyTorch implementation for the SIGIR2022 full paper "Contrastive Learning with Hard Negative Entities for Entity Set Expansion" (https://doi.org/10.1145/3477495.3531954), which was used to reproduce the study.

Original Repository: https://github.com/geekjuruo/ProbExpan

## Data

Wiki and APR data can be found here (https://drive.google.com/drive/folders/1-X4fJSQHgifl6WVkV0hGMurMA39fLZx8) and should be extracted into the `./ProbExpan/data/` folder. We've also added our results of the preprocessing for phases 1 and 3 as `./ProbExpan/data/wiki/entity2sents.pkl` and `cls2eids.pkl` respectively.

## Differences to the original repository

Naming conventions for file locations have been altered, to reflect the structur of the downloaded data. Additionally, we've included our trained models with and without CL in the folder `./model_wiki1/`, which can be used to reproduce the learning phases 2 and 4 respectively. Results of our phases 2 and 4 have also been added in the folders `./ProbExpan/data/wiki/ensemble+winodw+rank` and `./ProbExpan/data/wiki/cl+ensemble+winodw+rank`.