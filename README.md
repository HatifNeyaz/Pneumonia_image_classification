# Pneumonia X-Ray Image Classification task

## Aim is to correctly classify Pneumonia using a CNN model & visualize the area where model focuses for prediction

#### X-Ray images after simple Transformation:

![Transformation](model_images/only_transformed.png)


#### Loss and Accuracy during training and validation:

Training Loss: 0.3567 
Training Accuracy: 0.8436

Validation Loss: 0.5079
Validation Accuracy: 0.8125


#### Confusion Matrix:

![Confusion_Matrix](model_images/Confusion_matrix.png)

True Positives = 318
True Negative = 201

False Positive = 33
False Negative = 72

#### ROC Curve:

![ROC Curve](model_images/Roc_auc_curve.png)

#### Pytorch 'Hooks' function is used to focus in the last convolutional layer 
#### so we can visualize the image from model's perspective

![Model_vision](model_images/focus.png)




