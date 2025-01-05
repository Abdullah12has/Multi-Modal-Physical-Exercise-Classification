# Multi-Modal-Physical-Exercise-Classification
In this project, real multi-modal data is studied by utilizing different techniques presented during the course. In addition, there is an optional task to try some different approaches to identify persons from the same dataset. Open MEx dataset from UCI machine learning repository is used. 

The 4 columns in the *act* files are organized as follows:
1 - timestamp
2 - x value
3 - y value
4 - z value
Min value = -8 
Max value = +8 


The 193 columns in the *dc* file is organized as follows: 
1 - timestamp 
2-193 depth camera data frame (12x16) 
dc data frame is scaled down from 240x320 to 12x16 using the OpenCV resize
algorithm 
Min value - 0
Max value - 1
