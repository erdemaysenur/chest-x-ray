### README
#### Pneumonia Detection
![](https://i.imgur.com/jZqpV51.png)


 An image classification sample to classify normal/pneumonia from x-ray images. 
 
 Data augmentation was used to prevent overfitting but because of the type of images only brightness_range has been set.(shearing or shifting wouldn't be helpful)

#### Result
86% accuracy was performed on test images.

#### Dataset
[Chest X_Ray Images](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

##### References
I used this well-performed cnn model from [this notebook](https://www.kaggle.com/madz2000/pneumonia-detection-using-cnn-92-6-accuracy).
