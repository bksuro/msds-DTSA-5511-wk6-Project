# msds-DTSA-5511-wk6-Project

## Description
Purpose of this project is to predict who would be a viable candidate to donate for charity based on the data provided. Using Neural Network models to come up with a good model with good prediction score.

4 different models were used

### Model 1
Started with only 43 features, and 2 hidden layers and used relu and sigmoid for activation.

Then further re-processing is done before implementing models 2, 3, and 4.

### Model 2
Model 2 has 238 features amd 2 hidden layers with relu for hidden layers and sigmoid for output layers as activation.

### Model 3
This model has one additional feature making them 239, with 4 hidden layers. Activations used are 'relu', 'tanh', and 'sigmoid'

### Model 4
Model 4 has same features as model 3, 239, and 4 hidden layers. However, activations used were in a different order.


### Accuracy Score

TRAIN
Model|Accuracy|Loss|Layers
-----|--------|----|------
 1| 74.10% | 53.53% | 2
 2| 79.82% | 41.54% | 2
 3| 79.65% | 42.29% | 4
 4| 79.88% | 41.62% | 4


TEST
Model|Accuracy|Loss|Layers
-----|--------|----|------
 1| 72.50% | 55.86% | 2
 2| 78.08% | 69.81% | 2
 3| 77.88% | 45.76% | 4
 4| 77.97% | 46.92% | 4
