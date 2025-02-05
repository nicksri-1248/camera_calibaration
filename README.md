# COMPUTATION OF CAMERA PARAMETERS

## Description
Camera calibration is the process of determining a camera’s intrinsic and extrinsic parameters to ensure geometric accuracy in captured images. The intrinsic parameters describe the internal characteristics of the camera, such as its focal length, optical center (principal point), and lens distortion coefficients. Extrinsic parameters, on the other hand, define the camera’s position and orientation relative to the 3D world. The purpose of calibration is twofold: to correct lens distortions and to establish the mathematical.

## Features
- To compute intrinsic parameters matrix, containing focal lengths, principal point coordinates, and skew coefficient. 
- To compute Extrinsic Parameters as rotation and translation vectors were for each image.

## Installation
Step-by-step instructions on how to install and set up the project.

```sh
# Terminal Command
python -m pip install --upgrade pip
python -m pip install jupyter
python -m notebook

#Jupyter Notebook Command
!pip install opencv-python numpy scipy matplotlib
