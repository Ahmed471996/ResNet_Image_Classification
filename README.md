# ResNet_Image_Classification

## Introduction
we will be building ResNet. We are building this CNN from scratch in PyTorch, and will also see how it performs on a real-world dataset.

We will start by exploring the architecture of ResNet. We will then load and analyze our dataset,  CIFAR-10 , using the provided class from torchvision. Using PyTorch, we will build our ResNet from scratch and train it on our data. Finally, we will see how the model performs on the unseen test data.

## ResNet
VGG focuses on another crucial aspect of Convolutional Neural Networks (CNNs), depth. It was developed by Simonyan and Zisserman. It normally consists of 16 convolutional layers but can be extended to 19 layers as well (hence the two versions, VGG-16 and VGG-19). All the convolutional layers consists of 3x3 filters. You can read more about the network in the official paper.

![image](https://user-images.githubusercontent.com/101316217/210557257-822effd5-9c5c-4c5a-a331-513d6e02bba8.png)

## Dataset
we will be using the famous CIFAR-10 dataset, which has become one of the the most common choice for beginner computer vision datasets. The dataset is a labeled subset of the 80 million tiny images dataset. They were collected by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. The classes are completely mutually exclusive. There is no overlap between automobiles and trucks. "Automobile" includes sedans, SUVs, and things of that sort. "Truck" includes only big trucks. Neither includes pickup trucks.

Here are the classes in the dataset, as well as 10 random images from each:


![image](https://user-images.githubusercontent.com/101316217/210557280-56badf32-aacd-44c3-88f2-5dff915f9f37.png)

## Tools
PyTorch

Colab

## Future Work
You can try using different datasets.

You can experiment with different hyperparameters and see the best combination of them for the model.
