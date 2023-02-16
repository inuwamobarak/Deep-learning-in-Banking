# Deep learning in Banking: Colombian Peso Banknote Detection

## Problem Statement
As we have discussed in the introduction, it is a challenge for most individuals to tell between a fake banknote and a genuine one. Most people do not have any skill in this area and can get easily fooled into exchanging their good currency for fakes by scammers. We will embark on the challenge of solving this problem by using original and fake Colombian banknotes made available professionally for research.

The Colombian peso (sign: , with Col$. also being used to distinguish it from other peso- and dollar-denominated currencies. (Wikipedia)

## Approach
In this project, Deep learning algorithm is used to predict fake COP banknotes. The core library is PyTorch. Transfer learning was used to transfer weights from the ResNet series of pretrained models.

![money-1292162_1280](https://user-images.githubusercontent.com/65142149/219488704-f873733c-46c9-4a4b-8b76-759c93f646d8.jpg)

## About the dataset
**Description**
The dataset can be used to check for the detection of denominations and counterfeits in banknotes.
* The dataset consists of 20800 images, which contain 13 classes, where 6 correspond to original banknotes, another 6 to counterfeits, and 1 additional category for the background.
* It contains illumination variations, rotation, and partial views of the banknotes. Contains 3 folders each of 20800 images, corresponding to ds1, ds2, and ds3.
* Each folder contains a training, validation, and test sub-folder, which contains the images.
* All classes are balanced in the number of images.
