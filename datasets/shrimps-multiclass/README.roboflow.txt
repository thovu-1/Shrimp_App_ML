
Dwarf-Shrimp Detection Dataset  - v11 2023-05-05 11:17am
==============================

This dataset was exported via roboflow.com on May 12, 2023 at 5:21 PM GMT

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

The dataset includes 26822 images.
Dwarf-Shrimp are annotated in Multi-Class Classification format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* Random shear of between -9° to +9° horizontally and -10° to +10° vertically
* Random brigthness adjustment of between -33 and +33 percent
* Random exposure adjustment of between -30 and +30 percent
* Salt and pepper noise was applied to 5 percent of pixels


