# Image Classification with CIFAR-100

## Project Summary
We are a startup that builds machine learning models to help classify images. Specifically, we specialize in CNN models used to cluster and classify objects in aerial photographs and satellite images.

For this project, we plan to start with classification of objects into 10 labels as specified by the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html) and, if time permits, to enhance our model to detect and classify different types of the same object into broader categories like animals vs non-animals.

## Dataset Description

For the final project, we will use CIFAR-10 (Canadian Institute for Advanced Research, 10 classes, named after the funder of the project)  by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton as our dataset for analysis. CIFAR-10 consists of 60,000 labeled color images in 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck), with 6,000 images per class. Each image is 32x32 pixels, which has a higher resolution than those in many of the other open data sources while remaining small in size when compared to some of the more recent image databases. The dataset is divided into a training subset of 50000 images and another test subset of 10000. The 10 classes are mutually exclusive, and there is no overlap between images.

## Repository Structure

**reports:** includes final project notebooks for submission
1. **w207_cifar10_final_project_report.ipynb**: Final report containing EDA, and custom CNN model development
2. **transfer_learning_w207_cifar10_final_project.ipynb**: Extension to final report containing VGG16, ResNet50 experimentation
3. **preprocessing_with_cnn_model3.ipynb**: Extension to final report containing impact of data augmentation & preprocessing procedures

**eda**: includes summary EDA and visualizations for CIFAR-10 dataset

