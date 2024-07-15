# Face detection task

This script used a pre-trained MTCNN(Multi-task Cascaded Convolutional Networks) to do the face detection in images. 

All the files (scripts, sample images, sample processed images) are in the shared google folder with the shared link: https://drive.google.com/drive/folders/1sXL6jUY6Up0O04ZJk5SFINzCYM0oWoLb?usp=sharing 

## Usage
To run the face detection script, follow these steps:

 - Prepare image dataset: Place all images you want to process in the inputs directory.
 - Run the script
 - Check the outputs: Processed images will be saved in the outputs directory with bounding boxes.Bounding box coordinates are stored in outputs/bounding_boxes.txt.

## Note
In the code, I used a sample of images from the FDDB dataset and the bounding boxes from the FDDB-folder as true values to test the accuracy of this pre-trained MTCNN on this sample.
