# PlantDisease_Final

## Abstract :
Convolutional neural network models were developed to perform plant disease detection and diagnosis using simple leaves images of healthy and diseased plants, through deep learning methodologies. Training of the models was performed with the use of an open database of 19,721 images, containing different plants in a set of 15 distinct classes of [plant, disease] combinations, including healthy plants. Several model architectures were trained, with the best performance reaching a 93.6% success rate in identifying the corresponding [plant, disease] combination (or healthy plant). The significantly high success rate makes the model a very useful advisory or early warning tool, and an approach that could be further expanded to support an integrated plant disease identification system to operate in real cultivation conditions.

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

## Scope of the project
Plant diseases cause a major production and economic losses in the agricultural industry. The disease management is a challenging task. Usually the diseases or its symptoms such as coloured spots or streaks are seen on the leaves of a plant. In plants most of the leaf diseases are caused by fungi, bacteria, and viruses. The diseases caused due to these organisms are characterized by different visual symptoms that could be observed in the leaves or stem of a plant. Usually, these symptoms are detected manually.
With the help of CNN, Automatic detection of various diseases can be detected with the help of CNN. CNN plays a crucial role in the detection of plant diseases since it provides best results and reduces the human efforts. The CNN could be used in the field of agriculture for several applications. It includes detection of diseased leaf, stem or fruit, to measure the affected area by disease, to determine the colour of the affected area. Tomato cultivation is one of the most remunerative farming enterprises in India. The naked eye observation by the experts is approach usually taken in identification and detection of plants. This approach is time consuming in huge farms or land areas. The use of CNN techniques in detection and identification of Different plant diseases in the earlier stages and thereby the quality of the product could be increased. These systems monitor the plant such as leaves and stem and any variation observed from its characteristic features, variation will be automatically identified and also will be informed to the user.

## Tools Used : 

colab
Keras 
matplotlib 
numpy 
opencv-python
python
tensorflow-gpu
