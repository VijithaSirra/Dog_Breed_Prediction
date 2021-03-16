# <div align="center"> Dog Breed Prediction </div>
<p align="center">
  <img src="image.jpg">
</p>

THis Repo Contains Classification using ResNet50 for Dog Breed Prediction. This Determine the breed of a dog in an image

Data Set Source : Dog Breed Image dataset from Kaggle Dog Breed Identification compitation. <br>

Here goal is to create a classifier capable of determining a Dog’s breed from an Image. 

The dataset comprises 120 breeds of dog. The number of dogs in each breed ranges between 60 and 130. 

In this Repo, contains a classification model Trained in Google Colab to classify the 10 Dog Breeds 

- Beagle
- Chihuahua
- Doberman
- French Bulldog
- Golden Retriever
- Malamute
- Pug
- Saint Bernard 
- Scottish Deerhound
- Tibetan Mastiff

After extracting only these 10 Dog breeds from the Dataset, the Dataset size became less. 

Used Image Augmentation to increase size of the Dataset. 

After Augumentation, the whole Dataset size increased to 7000+

Augmentaion Processes :  Increasing Brighness, Change in Angle, Cropping, and Flipping 
 
Used ResNet50 Architecture which includes :

- Conv2d
- ReLu Activation Function
- Bacth Normalization
- Maxpooling
- AveragePooling 
- Softmax layers

And used Categorical Crossentropy as loss function , And Adam as an Optimizer.

#### Got 98% Training Accuracy and 80% Testing Accuracy by using ResNet50. 

### Dataset: [Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)


### Training: [Training Classification Model](https://github.com/VijithaSirra/Dog_Breed_Prediction/blob/main/Dog_Breed_Train.ipynb)

### Inference: [Inference Code](https://github.com/VijithaSirra/Dog_Breed_Prediction/blob/main/Inference.ipynb)

### Further Improvements: 
- To Use L1, L2 Regularizers 
- To Use Dropout Layers
