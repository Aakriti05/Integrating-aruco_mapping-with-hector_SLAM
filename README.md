# Integrating-aruco_mapping-with-hector_SLAM
Localization using aruco markers on the map built by hector_slam with aruco markers inserter in it.

It is divided into two stages. Only stage one is implemented in this repository. Stage 1 and 2 both have been done in the form of Gazebo Simulation in another repository. 
Stage1 : Mapping using hector_slam with realtime insertion of aruco markers in the map.
Stage2 : The above map is loaded. Path-planning and localization has been done with using only aruco markers and odometry in real-time. Aruco_markers estimate pose which is used to correct the drift in odometry calculation.

## System Specifications
ros-indigo
ubuntu 14.04
lizi robot

## Packages used and modified
Hector_slam
Robotican (old package for lizi. No more available on their website)
aruco_mapping

## STAGE 1 

## STAGE 2
