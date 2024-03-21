
# Deep Learning for Time-Series Prediction

This repository contains the implementation and analysis of LSTM and RNN models for time-series prediction, focusing on forecasting the number of international airline passengers. This project is part of the ENPM690 coursework at the University of Maryland.

## Overview

The project explores the use of Long Short-Term Memory (LSTM) and Recurrent Neural Network (RNN) models to predict future values in a time-series dataset. The dataset consists of the monthly totals of international airline passengers from 1949 to 1960.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- Numpy
- Pandas
- Matplotlib

### Installation

Clone the repository to your local machine:


[git clone https://github.com/<your-username>/<your-repository>.git
](https://github.com/cravotics/Time-series-prediction.git)Install the required Python packages:


pip install torch torchvision numpy pandas matplotlib

- The dataset can be accessed here in contents. It is automatically downloaded when running the scripts.

## Usage
- Run the Python notebooks provided in the repository to train and evaluate the LSTM and RNN models:

## LSTM_RNN_Time_Series_Prediction.ipynb: Notebook containing the entire pipeline, from data preprocessing to model evaluation.
- Models
  - LSTM Model
- Input Layer
  - LSTM Layer (hidden_size = 50, num_layers = 1)
  - Fully Connected Layer (output_size = 1)
- RNN Model
 - Input Layer
 - RNN Layer (hidden_size = 50, num_layers = 1)
 - Fully Connected Layer (output_size = 1)

## Results
Both models were trained on the dataset, and their performance was evaluated using RMSE, MAE, and MAPE metrics. Detailed results and comparisons can be found in the notebook.



