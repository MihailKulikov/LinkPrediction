# Link Prediction
Data and results of the second-year semester practice.

## Problem statement
it is necessary to predict the probability of collaboration between a pair of authors.

## Data
The dataset contains information about the articles of the journal "Oil industry" written in the period from 2012 to 2017.

## Results
Optimization was performed using the F3 metric.
| Model               | Precision | Recall | ROCAUC | PRAUC | F3    |
| :-------------:     |:---------:|:------:|:------:| :---: | :----:|
| Logistic regression | 0.378     | 0.646  | 0.97   | 0.5   | 0.6   |
| SVM                 | 0.33      | 0.65   | 0.97   | 0.52  | 0.595 |
| GBM                 | 0.357     | 0.63   | 0.968  | 0.54  | 0.586 |
| Random forest       | 0.44      | 0.53   | 0.94   | 0.507 | 0.52  |
| SEAL (GNN)          | 0.24      | 0.34   | 0.75   | 0.19  | 0.33  |
