# Flower-Image-Classifier

The repository contains the code for an image classifier that identifies different species of flowers. The model was submitted as the final project for [Facebook PyTorch Scholaship Challenge](https://in.udacity.com/facebook-pytorch-scholarship). 

### The Dataset

The data set contains images of flowers from 102 different species, split into a training set and a validation set. You can [download the images from here](https://s3.amazonaws.com/content.udacity-data.com/courses/nd188/flower_data.zip) as a zipped archive. Just uncompress it and you should be good to go.

### Instructions for Google Colab

1. [Click here](http://colab.research.google.com) to open Google Colab
2. Paste the notebook link under the _Github_ tab, or alternatively, download the notebook and upload it to Colab.
3. Enable GPU: Go to Edit -> Notebook settings and select GPU as the hardware accelarator.
4. Run all the code cells

### About

Initially, the model chosen was _VGG19_, which was later shifted to _Resnet 152_ for better accuracy. Hence, the two files, `Image Classifier Project — VGG19.ipynb` and `Image Classifier Project — ResNet-150.ipynb`.

Further details can be found in the notebook itself.
