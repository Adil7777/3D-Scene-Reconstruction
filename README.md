# 3D-Scene-Reconstruction
This repository is a solution for an assignment regarding 3D Scene Reconstruction for EE 417 course
This repo contains two .ipynb files, 2 folders with images and 1 txt file with camera intrinsic matrix

"camera_calibration.ipynb" contains a code to calculate camera intrinsic matrix. 
It used the images of chess board pattern that are in the folder "calibration_images". 
After the camera intrinsic matrix is calculated, it saves it in the "camera_calibration.txt" file.

"main.ipynb" file contains the main pipeline, computing key features, fundamental matrix,
essential matrix, and triangulation. 

"images" folder contain the main 2 images that were used in the "main.ipynb".
