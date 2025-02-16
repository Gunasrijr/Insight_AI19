
UPD - v1 2022-07-24 12:50am
==============================

This dataset was exported via roboflow.com on July 23, 2022 at 11:52 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 1220 images.
Plastic are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 5 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 49 percent of the image
* Random exposure adjustment of between -22 and +22 percent
* Random Gaussian blur of between 0 and 3.25 pixels


