# Climate Prediction with Deep Learning Models

This repository contains the code and results for predicting surface air temperature (TAS) and precipitation (PR) from climate image data using various deep learning architectures.

## Overview

- The main notebook `cse151BFinalCompetitionNotebook.ipynb` includes all the code used to train models and generate the submission for the competition.
- The project compares five models: Simple CNN, UNet, ResNet, DenseNet, and Attention UNet.
- Among these, **Attention UNet** achieved the best performance in terms of validation RMSE and was used for the final submission.

## Folder Structure

- `attentionUNetTrialOutputs/` — training logs, loss plots, and best model results for Attention UNet.  
- `denseNetTrialOutputs/` — training and validation results for DenseNet.  
- `unetTrialOutputs/` — training and validation results for UNet.  
- `resNetTrialOutputs/` — training and validation results for ResNet.  
- `simpleCNNTrialOutputs/` — training and validation results for Simple CNN.

Each folder contains loss plots and metrics for multiple hyperparameter tuning attempts, including the best-performing configurations.

## Highlights

- The best model (Attention UNet) achieved the lowest validation RMSE for TAS and PR.  
- Detailed loss plots and validation scores for the best Attention UNet model can be found at:  
  `attentionUNetTrialOutputs/attentionUnetTrialBest/`

## Usage

Run the `cse151BFinalCompetitionNotebook.ipynb` to reproduce training, evaluation, and submission steps.
