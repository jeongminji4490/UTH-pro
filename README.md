# UTH-pro
###### This program is a Hand gesture authentication program written by Python.
###### And I created CNN model for hand gesture authentication.
#### The program structure is as follows:
###### 1. cnn model saved in h5 format
###### 2. Main program to authenticate hand gestures
###### :bulb: Caution ) This model is a model whose true value has already been determined. So the true value cannot be modified. Here is the true value image:
![3](https://user-images.githubusercontent.com/62979330/146676289-eb5fc9dc-4c03-44ee-9c4d-4d8b4d3fc992.jpg)

#### CNN Model 
##### 1. Dataset
###### I got 13000 false images and 907 true images from the following sites.
[11k Hands](https://sites.google.com/view/11khands)
[Roboflow](https://public.roboflow.com/classification/rock-paper-scissors/1)
[Kaggle](https://www.kaggle.com/drgfreeman/rockpaperscissors)
##### 2. Normalization
###### All images used for training were binarized before preprocessing.
###### false image example:
![Untitled (4)](https://user-images.githubusercontent.com/62979330/146676638-f3b534fc-cc01-4da8-9db0-504aa3ccf918.png)
![Untitled (5)](https://user-images.githubusercontent.com/62979330/146676639-65aeb5ea-17ca-4999-91f0-e5122fe280bc.png)
###### true image example:
![Untitled (6)](https://user-images.githubusercontent.com/62979330/146676663-5b3134ec-e5ca-4dc0-94bf-0ec1aebd6796.png)
