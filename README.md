# PneumoAI
Bianary detector of pneumothorax on X-ray chest scans

Pneumothorax is a potentially life-threatening condition that requires prompt recognition and often urgent intervention, AI models could be able to detect pneumothorax conditions faster and more accurately than radiologists.

## Disclamer 
#### This is not a reliable model and should not be used for any medical application, only for learning purposes 

## Accuracy
This model as a very limited accuracy, it can be explained by the very small data set that I used (250 DICOM files)

#### Specificity = True Negative/(False Positive + True Negative) = 93% 
The model has a specificity of 93% and hence can correctly detect 93% of the time that a patient does not have Pneumothorax but will incorrectly classify that 7% of the patients have Pneumothorax (False Postive) but actually do not.

#### Negative Predictive Value (NPV) = 63%
The model will classidy people with no No Pneumothorax 63% of the time


Link to the paper: https://doi.org/10.1007/s10278-019-00299-9

![image](https://bucket.mlcdn.com/a/3464/3464429/images/32e716400b95b9d67f7386ed7d6865795caaf0d9.png)
