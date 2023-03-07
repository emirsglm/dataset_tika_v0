
tika_beta1 - v6 2023-03-01 1:57pm
==============================

This dataset was exported via roboflow.com on March 7, 2023 at 9:46 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 730 images.
Plants are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 256x256 (Stretch)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Random rotation of between -16 and +16 degrees
* Random shear of between -9° to +9° horizontally and -12° to +12° vertically
* Random brigthness adjustment of between -20 and +20 percent
* Random exposure adjustment of between -27 and +27 percent


