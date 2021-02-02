# PlantDisease_Final

## Date Description : 
We have 15 Different classes here in our dataset :

    class 0 : "Plant Name : Pepper bell | Disease : Bacterial spot"
    class 1 : "Plant Name : Pepper bell| No Disease : healthy"
    class 2 : "Plant Name : Potato | Disease : Early blight"
    class 3 : "Plant Name : Potato | Disease : Late blight"
    class 4 : "Plant Name : Potato | No Disease : healthy"
    class 5 : "Plant Name : Tomato | Disease : Bacterial spot"
    class 6 : "Plant Name : Tomato | Disease : Early blight"
    class 7 : "Plant Name : Tomato | Disease : Late blight"
    class 8 : "Plant Name : Tomato | Disease : Leaf Mold"
    class 9 : "Plant Name : Tomato | Disease : Septoria leaf spot"
    class 10 : "Plant Name : Tomato | Disease : Spider mites Two spotted spider mite"
    class 11 : Plant Name : Tomato | Disease : Target Spot"
    class 12 : "Plant Name : Tomato | Disease : Yellow Leaf Curl Virus"
    class 13 : "Plant Name : Tomato | Disease : Mosaic Virus"
    class 14 : "Plant Name : Tomato | No Disease : healthy"


15 Classes == 15 types of diseases images are collected.
15601 Train Images
4119 Test images


For prediction, I took only a few samples from unseen data. 
we can evaluate using validation data which is part of train data.

## Tools Used : 

colab
Keras 
matplotlib 
numpy 
opencv-python
python
tensorflow-gpu

## Model : 
Our model takes raw images as an input, so we used CNNs (Convolutional Nural Networks) to extract features

Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_31 (Conv2D)           (None, 252, 252, 32)      2432      
_________________________________________________________________
max_pooling2d_9 (MaxPooling2 (None, 84, 84, 32)        0         
_________________________________________________________________
conv2d_32 (Conv2D)           (None, 82, 82, 32)        9248      
_________________________________________________________________
max_pooling2d_10 (MaxPooling (None, 41, 41, 32)        0         
_________________________________________________________________
conv2d_33 (Conv2D)           (None, 39, 39, 64)        18496     
_________________________________________________________________
max_pooling2d_11 (MaxPooling (None, 19, 19, 64)        0         
_________________________________________________________________
flatten_3 (Flatten)          (None, 23104)             0         
_________________________________________________________________
dense_9 (Dense)              (None, 512)               11829760  
_________________________________________________________________
dropout_3 (Dropout)          (None, 512)               0         
_________________________________________________________________
dense_10 (Dense)             (None, 128)               65664     
_________________________________________________________________
dense_11 (Dense)             (None, 15)                1935      
=================================================================

