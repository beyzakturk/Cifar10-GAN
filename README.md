# Cifar10

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.

Here are the classes in the dataset, as well as 10 random images from each:

![image](https://miro.medium.com/max/1182/1*OSvbuPLy0PSM2nZ62SbtlQ.png)

The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

## Download
If you're going to use this dataset, please cite the tech report at the bottom of this page.
Version:
- [CIFAR-10 python version](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz)	163 MB	
- [CIFAR-10 Matlab version](https://www.cs.toronto.edu/~kriz/cifar-10-matlab.tar.gz)	175 MB	
- [CIFAR-10 binary version](https://www.cs.toronto.edu/~kriz/cifar-10-binary.tar.gz) (suitable for C programs)	162 MB	
 
## Baseline results
You can find some baseline replicable results on this dataset on the project page for cuda-convnet. These results were obtained with a convolutional neural network. Briefly, they are 18% test error without data augmentation and 11% with. Additionally, Jasper Snoek has a new paper in which he used Bayesian hyperparameter optimization to find nice settings of the weight decay and other hyperparameters, which allowed him to obtain a test error rate of 15% (without data augmentation) using the architecture of the net that got 18%.

## Other results
Rodrigo Benenson has been kind enough to collect results on CIFAR-10/100 and other datasets on his website
