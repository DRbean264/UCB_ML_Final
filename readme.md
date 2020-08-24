This is a demo for how to deploy models trained by AutoML and Transfer Learning on edge device.
Our device is HUAWEI Honor V8, Android 8.0.0.
The dataset is created by Jeremy, Alan and Calvin.

In the folder "Dataset_Construction", you will find how we extract each frame from videos to 
construct our dataset. There are also codes used for data augmentation, which currently contains 
image flipping, image rotation, color enhancement, contrast enhancement, brightness enhancement, 
Gaussian noise. 

In the folder "Deployment", I put several website which contains the official tutorial of deployment
on edge device. But it's incomplete and the application won't work on the phone if you trained your
own models. So there's another link which shows the correct change of codes

In the folder "Google_Cloud_API", you can find the method that create a .csv file according to the 
structure of dataset folder. This is used in automl which requires such csv file to load all the images.

In the folder "Models_Labels", I upload all the models we've trained and you can use it to directly 
deploy on your android device.

In the folder "Result_Pics", I show the results of all 37 different gestures.

In the folder "Transfer_Learning", I upload a jupyter notbook in which contains our code of transfer 
learning.
