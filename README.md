# ECE 196 Presentation Files

Contains the files needed for the ECE 196 class session. All files actually are already completed, but they are to be reviewed more thoroughly during the class session.

## Files
- CNN_Demo.ipynb
    - Contains some basic CNN example + basic result analysis.
- MLP_Demo.ipynb
    - Contains a basic MLP implementation.
- Face_Recognition_Demo.ipynb
    - Covers the face recognition application along with a couple examples of different parts of the typical pipeline for classification. Uses VGG16 and YOLO as bases.
    - ***Note***: Make sure you have an extra 500 MB of space in order to accomodate the weights file for YOLO.

The presentation that accompanies the above material can be found in the repository as well under the Presentation directory.

## Required Packages
- tensorflow > 2.0
- tensorflow-addons
- opencv-python-contrib
- matplotlib
- numpy > 1.8
- seaborn
- sklearn
- tqdm (Optional)

You can install all of them through **pip** or **conda** if you have Python 3.8. Make sure to use a virtualenv or conda env if you would like to easily remove all of these packages later.

## References
- [YOLO V3](https://github.com/zzh8829/yolov3-tf2) - YOLO (You-Only-Look-Once) implementation using TF 2.0. The YOLO network used here pretty much uses this repository as a base.