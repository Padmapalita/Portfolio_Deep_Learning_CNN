# Portfolio_Deep_Learning_CNN
A collection of google colab notebooks used to develop unique convolutional neural networks (CNNs) for image classification tasks

## CIFAR10_Lotus_Model_CNN.ipynb
Contains a CNN developed to maximise accuracy on the CIFAR-10 image set. The specification for this model was created by a deep learning research to ensure our work was original. The model achieved 95.17% accuracy which would place it at rank 125 in the papers with code https://paperswithcode.com/sota/image-classification-on-cifar-10 and achieve parity with state-of-the-art in 2019-2020. 

## CIFAR100 - Lotus model (unmodified) - CNN.ipynb
Takes the unmodified Lotus Model developed in CIFAR10_Lotus_Model_CNN.ipynb and tests its generalisability to a different but similar task, the CIFAR-100 set. 
The model showes a 7,211% improvement over the inital (random) prediction likelyhood, giving an indication of the models maximum utility. It is clear from the training curves that more tuning of the iamge augmentation/transformation could improve the accuracy with reached 72.11%
Despite this, according to papers with code, https://paperswithcode.com/sota/image-classification-on-cifar-100 the unmodified version of the lotus model would rank 152 in its list, achieving parity with state-of-the-art in 2015.
