# Essay Quality Prediction with Keystroke Analysis


## Introduction

This repository houses a Deep learning models that harnesses the power of keystroke analysis to predict the quality of essays. By extracting insights from users' typing behaviors during the writing process.

## Dataset 

The dataset comprises approximately 5000 logs of user inputs, including keystrokes and mouse clicks, recorded during the creation of essays. Each essay is scored on a scale of 0 to 6. The challenge is to predict the score an essay received based on its log of user inputs.


## Model Architecture 

The model is constructed using LSTM and Transformer.


## Dependencies 

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Tensorflow
- Keras-nlp

## Results 

- Mean Squared Error for Transformer after 80 epochs : 0.0257
- Mean Squared Error for LSTM after 200 epochs :  0.0143
