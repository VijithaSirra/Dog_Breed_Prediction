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

I got only few images After extracting these breeds from the Data Set. Then I Augumented existed images to 7k+ by Increasing Brighness, Change in angle, Cropping, and Flipping .  

I used ResNet50 Architecture which includes Conv2d, ReLu Activation Function, Bacth Normalization, Maxpooling, AveragePooling and Softmax layers. And I used Categorical Crossentropy as loss function , And Adam as an Optimizer.

I got 98% Training Accuracy and 80% Testing Accuracy by using ResNet50. 

### DataSet:
[Dog Breed Identification](https://www.kaggle.com/c/dog-breed-identification/data)
