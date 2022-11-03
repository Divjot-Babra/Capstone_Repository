# Capstone Repository

This repository contains relevant files for the engineering capstone subject.  
###### Author: Divjot Singh Babra

### Program Overview
The program filters and sorts pedestrian data from the provided rosbags into a data table. The features of each pedestrian are then plotted. Probability distribution plots and joint probability distribution plots are populated using the organised data. These plots are then used to find corresponding pedestrians between cameras. The tracks of each identified pedestrian are then time synchronised and stored into another data table. Extrinsic calibration is then performed using the individual tracks of each identified pedestrian. Plots are also created to show the results of the point cloud registeration process. Calibration is then performed using a combination of pedestrian tracks. Finally, calibration is performed using the corresponding tracks of all identified pedestrians. Using these results, the estimated pose of the camera is plotted against the actual known pose of the camera. 

Refer to the Engineering Capstone Report for further details. 

### Instructions for Running Program
1. Clone the repository using the appropriate method.
2. Open 'CapstoneProgram.mlx' file using MATLAB. The program was developed on MATLAB 2022a.
3. Ensure the following rosbags are within the current folder:
- 2022-08-29-21-10-20.bag
- 2022-08-29-21-28-22.bag
4. Run the complete MATLAB live script.

###### Date: November 2022
