# Image_Segmentation_using_DeepLabV3
### Project Overview
This project uses the DeepLabV3 model with a ResNet50 backbone, which has been pre-trained on a variety of images, to provide an improved method of semantic image segmentation. The model is loaded, photos are preprocessed, inference is carried out, and the outcomes are visually represented by modular functions that are organized into distinct sections of the code. 
# Features
### Model Loading: 
Uses the PyTorch hub to load a DeepLabV3 model that has been trained and is very accurate in semantic segmentation. 
### Image preprocessing:
It involves scaling, normalizing, and converting images into a tensor format that may be used as an input for models.
### Semantic Segmentation:
Semantic Segmentation Inference classifies each pixel into one of 21 classifications and uses the loaded model to perform segmentation on images in order to identify various contextual factors.
### Visualization: '
It shows the original image side by side with the segmentation map that corresponds to it, demonstrating how well the model is able to identify various objects in the image.

# How to Run the Project:
