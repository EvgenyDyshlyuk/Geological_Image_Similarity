# Gelogical Image Similarity
**This is a personal ML project on [Geological Image Similarity Dataset](https://www.kaggle.com/tanyadayanand/geological-image-similarity)**  

## BACKGROUND
A geology research company wants to create a tool for identifying interesting patterns in their imagery data. This tool
will possess a search capability whereby an analyst provides an image of interest and is presented with other images
which are similar to it.

## GOAL
Task is to create the machine learning component for this image similarity application. The machine learning
model should return the top K images that are most similar to this image based on a single image input.

## About the Data:
The data includes 6 different classes of 5000 28X28 RGB images (total of 29998 images)


## Solution
Simple classification task is solved for 6 classes of the dataset. The output for the penultimate layer is also provided as output of the CNN and is used as embedding to find the similarity between the images (using cosine similarity)

![figure](https://github.com/EvgenyDyshlyuk/Geological_Image_Similarity/blob/master/figures/CNN.png)
