# Multi-Modal-Physical-Exercise-Classification
In this project, real multi-modal data is studied by utilizing different techniques presented during the course. In addition, there is an optional task to try some different approaches to identify persons from the same dataset. Open MEx dataset from UCI machine learning repository is used. 

The 4 columns in the *act* files are organized as follows: <br/>
1 - timestamp <br/>
2 - x value <br/>
3 - y value <br/>
4 - z value <br/>
Min value = -8 <br/>
Max value = +8 <br/>


The 193 columns in the *dc* file is organized as follows: <br/>
1 - timestamp <br/>
2-193 depth camera data frame (12x16) <br/>
dc data frame is scaled down from 240x320 to 12x16 using the OpenCV resize
algorithm <br/>
Min value - 0 <br/>
Max value - 1 <br/>
