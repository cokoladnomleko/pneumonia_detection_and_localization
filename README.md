# Pneumonia Detection and Localization

This repository contains code for a two-part model for detection and localization of pneumonia on x-ray images. Detection is done using a self-made CNN (built in PyTorch) trained on Google Colab, and localization is done using the pre-trained YOLOv3 model - available [here](https://pjreddie.com/darknet/yolo/).

Training and testing was done using the images from the [RSNA Pneumonia Detection Challenge](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge).


### Results

Test images | Precision | Recall | Accuracy | F1 score
------------ | ------------- | ------------- | ------------- | -------------
500 pneumonia, 250 normal, 250 other diseases | 76.73% | 91% | 81.7% | 83.26%
500 pneumonia, 500 normal | 95.59% | 91% | 93.4% | 93.24%

Mean IOU was 0.271.
