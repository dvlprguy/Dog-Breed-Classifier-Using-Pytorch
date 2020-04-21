# Dog Breed Classifier using Resnet50 in Pytorch

A DeepLearning model that I made using resnet50, Cascade Classifier and VGG16. This model can detect humans, dogs and both in images.

## Dataset

The dataset can be downloaded from the following sources:-

Dog Images: https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

Human Images: http://vis-www.cs.umass.edu/lfw/lfw.tgz;

Additionally, the data can also be found on Kaggle.

https://www.kaggle.com/c/dog-breed-identification/data

## Pretrained Models

* OpenCVs Cascase Classifier was used to detect humans:

        https://docs.opencv.org/trunk/db/d28/tutorial_cascade_classifier.html

* Pytorch was used to import the pretrained VGG16 and Resnet50:

        https://pytorch.org/docs/master/torchvision/models.html


## Comparison

I also trained a model from scratch using Pytorch's implementation of Convulution layers to specify how poorly these models perform as compared to pretrained ones.

## Results

My model was able to achieve 81% accuracy on the test dataset.

The final results and the training code used are included in the Jupyter Notebook dog_app.ipynb