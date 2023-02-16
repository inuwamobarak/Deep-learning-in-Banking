# Fake Colombian banknote detecttion
In this repository, deep learning algorithm is used to predict fake COP banknotes and deployed using streamlit. The core library is [PyTorch](https://pytorch.org). Transfer learning was used to transfer weights from the ResNet series of pretrained models.

The Colombian peso (sign: , with Col$. also being used to distinguish it from other peso- and dollar-denominated currencies. (Wikipedia)

In this project, Deep learning algorithm is used to predict fake COP banknotes. The core library is PyTorch. Transfer learning was used to transfer weights from the ResNet series of pretrained models.

# About the dataset
**Description**
The dataset can be used to check for the detection of denominations and counterfeits in banknotes.
* The dataset consists of 20800 images, which contain 13 classes, where 6 correspond to original banknotes, another 6 to counterfeits, and 1 additional category for the background.
* It contains illumination variations, rotation, and partial views of the banknotes. Contains 3 folders each of 20800 images, corresponding to ds1, ds2, and ds3.
* Each folder contains a training, validation, and test sub-folder, which contains the images.
* All classes are balanced in the number of images.

