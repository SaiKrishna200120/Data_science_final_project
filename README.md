# Data_science_final_project
final dessertaion University of Hertfordshire (23022047)

# Enhancing Image Classification with Vision Transformers
Project Summary:
This project explores the self-attention mechanism in Vision Transformers (ViT) and its impact on the performance of image classification tasks, especially compared to traditional Convolutional Neural Networks (CNNs). CNNs, while successful, rely heavily on convolutions and pooling operations, which can limit the model’s ability to capture long-range dependencies. In contrast, ViT models utilize a self-attention mechanism that processes the entire image globally, enabling them to potentially learn more complex features and relationships across an image. By investigating how the self-attention mechanism enhances performance, this project aims to understand the advantages and limitations of ViT in comparison to CNNs for image classification tasks.
Research Question:
How does the self-attention mechanism in Vision Transformers (ViT) enhance the performance of image classification tasks compared to traditional Convolutional Neural Networks (CNNs)? What are the pros and cons of ViTs compared to CNNs in terms of dataset size, training complexity, computational resources, and the ability to understand the context of an image?
Project Objectives:
1.	To analyze the fundamental differences between Vision Transformers (ViTs) and Convolutional Neural Networks (CNNs).
2.	To investigate the performance of ViTs on various image classification benchmarks and compare them to CNN-based models.
3.	To examine the pros and cons of using ViTs in terms of dataset size, computational requirements, and their ability to capture image context.
4.	To develop a comprehensive understanding of how ViTs can outperform CNNs in image classification tasks, especially for larger, more complex datasets.
Reference List:
• Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. A., Kaiser, Ł., & Polosukhin, I. (2017). Title: Attention is All You Need. 
• Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). Title: ImageNet Classification with Deep Convolutional Neural Networks. 
• Alexey Dosovitskiy, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani, Matthias Minderer, Georg Heigold, Sylvain Gelly, Jakob Uszkoreit, Neil Houlsby. Title: An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale.
Data Management Plan:

Overview of the Dataset: 
• CIFAR-100 Dataset: A collection of 60,000 32x32 RGB images in 100 classes (each with 600 images). The dataset is used for training and testing machine learning models for image classification tasks, The CIFAR-100 dataset was created by the Canadian Institute for Advanced. The CIFAR-100 dataset was introduced in 2009 by Alex Krizhevsky, Vinod Nair, and Geoffrey Hinton. Categories: The dataset is split into 20 superclasses, and each superclass contains 5 subclasses. This allows for multi-level classification challenges.Examples of superclasses include: animals, vehicles, outdoor objects, etc.Intended Use: CIFAR-100 is primarily used for testing the performance of image classification algorithms.
 • MNIST Dataset: A dataset of handwritten digits (0-9) with 60,000 training images and 10,000 test images, each image being 28x28 pixels in grayscale. Developed by the National Institute of Standards and Technology (NIST) and modified by Yann LeCun and colleagues. Released in 1998. Number of Classes: 10 classes (digits 0-9).Number of Images: 70000 images in total:60000 images for training,10000 images for testing.Intended Use: The MNIST dataset has been widely used as a starting point for evaluating and comparing the performance of various machine learning and deep learning algorithms, especially in the context of digit classification and useful exploratory data analysis and visualization
Data Collection:
Both datasets will be downloaded from their respective official sources:
 • CIFAR-100: CIFAR-10 and CIFAR-100 datasets 
• MNIST: Index of /exdb/mnist
Metadata:
CIFAR-100: 60,000 images (32x32 RGB). 
 MNIST: 70,000 images (28x28 grayscale). 
 Data files will be stored in .csv, .png, or .jpg format. • Expected total size: ~5GB
Ethical Requirements:
GDPR Compliance: The datasets used  do not contain personally identifiable information, so they do not come under GDPR.
UH Ethical Policies: The project will comply with the University of Hertfordshire's ethical guidelines, ensuring that the data used is publicly available and intended for research purposes.
Permission to Use Data: Both CIFAR-100 and minst are publicly available datasets, and permission for their use is implicitly granted through their usage terms.
Data Collection Ethics: The datasets were collected by their respective organizations (CIFAR by the University of Toronto and minst by nist) in an ethical manner, with appropriate permissions from the data sources.
