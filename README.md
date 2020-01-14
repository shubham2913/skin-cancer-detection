# skin-cancer-detection
 The goal of the project is to classify skin lesion images as malignant or benign based on interpretable features extracted 
 from the image. 
 
Approach : 240 images have been kept for training and 60 imagesfor testing. Both the train and test set contain equal 
proportion of benign and malignant images. To tune model specific features and access the accuracy of models, 5-fold cross 
validation has been used on training data. Area under the ROC(receiveroperator characteristics) curve has been used as the 
metric for accuracy. 
Information such as area and diameter of the mole/lesion, color contrast, aspect ratio have been extracted to create more 
interpretable features. Gradient boosting and random forest model have been trained on the features for classification. 

Best accuracy of 73.6% and 70% have been achieved on validation and test data respectively. Random forest performs best among
the 2 models on both validation and test data. 
