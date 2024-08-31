## Malaria Detection

###The Context:
Malaria is a life-threatening disease caused by Plasmodium parasites and early detection is crucial for effective treatment.
Accurate and timely diagnosis can significantly reduce mortality rates especially in regions with limited medical resources.
####The Problem Formulation:
The task is to use data science particularly Deep learning and image processing techniques to classify blood cells as either parasitized or uninfected.
The goal is to build a model that maximizes accuracy and minimizes false diagnoses with low computation cost.
####The Objectives:
The primary aim is to develop an accurate and efficient model that can automatically detect malaria-infected cells from microscopic images.
This model should assist healthcare professionals in countries with limited resources in diagnosing malaria quickly and accurately.
####The Key Questions:
How accurately can the model distinguish between parasitized and uninfected cells?
What is the optimal architecture and preprocessing techniques needed to achieve high accuracy?
How does data augmentation and model complexity affect performance on this specific dataset?
####Data Description:
There are a total of 24,958 train and 2,600 test images (colored) that we have taken from microscopic images. These images are of the following categories:
- Parasitized: The parasitized cells contain the Plasmodium parasite which causes malaria
- Uninfected: The uninfected cells are free of the Plasmodium parasites
