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
Follow these steps to get your local setup running with the image segmentation project using DeepLabV3:

## 1. Clone the Repository:
Open your terminal or command prompt. Change the directory to where you want the project to be cloned. Then run the following command to clone the repository:

#### git clone https://github.com/batool04/Image_Segmentation_using_DeepLabV3.git
This will create a directory named Image_Segmentation_using_DeepLabV3 in your current directory containing all the files from the repository.

## 2. Navigate to the Project Directory:
Change into the project directory:
#### cd Image_Segmentation_using_DeepLabV3

## 3. Install Dependencies:
Before running the script, you'll need to ensure you have Python and all the necessary libraries installed. If you haven't already installed these, you can install them using pip:
#### pip install torch torchvision pillow matplotlib

## 4. Run the Script:
Execute the main script by running:
#### python segmentation_script.py

