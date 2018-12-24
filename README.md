# Human-Protein-Atlas-Classification


Proteins are a vital part of human cellular system. Localizing proteins at a diseased body’s cellular level could help in understanding the biological phenomena and functions causing the disease. High Throughput fluorescence microscopic Imaging also known as HTI is a frugal and affordable way of localizing proteins. This technique takes microscopic pictures of proteins of interest by staining them with fluorescent antibodies. Human Protein Atlas project has taken initiative of labeling such images, thus providing a opulent source of information which could be very well harnessed by the power of computational analytics such as Deep Neural Networks or Convolutional Neural Networks ( CNNs). CNN is very powerful machine learning model to perform classification of images. We have implemented CNN using pre-trained network- InceptionV3, from scratch using Conv2d layers and also GapNet-PL for localizing proteins in human body cell. We have also carried out fine-parameter tuning of different models and performed comprehensive comparisons between above models. 



**Much of the code has been taken from kaggle competition submissions.**

Dataset could be found here - 

https://www.kaggle.com/c/human-protein-atlas-image-classification/data


The dataset used for conducting all the experiments originally belongs to Cell Atlas which is a subset of  Human Protein Atlas. This dataset is also provided by kaggle as a part of their competitions. It consists of nearly 30,000 training images and 10,000 test images each of size 512 x 512. There are 28 possible locations (also known as organelles ) where a protein could be localized in a human cell. For simplicity, we chose to work on only 4 out of 28 possible labels, which are highlighted in pink in the below table. 


I have used only a subset of dataset - 
After reducing the the classification to single label and converting the dataset such that it contains total of four possible locations in target, we got following number of samples : 
Training Set : 1452 samples (70% of complete dataset)
Validation Set : 312 samples (50% of testing set)

