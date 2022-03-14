# The hardware architecture for UAV


>IMPORTANT. If you read this message, this paper has been submitted for publication and is under review. For this reason, some files are hidden according to the terms accepted by the authors. Please access again later to have access to all the files. If you are an academic researcher interested in this line of research and wish to have immediate access to all the files, please request it directly through the email address: aassilva@inf.ufrgs.br

<!---
This package presents the software solution for generating and sharing dynamic maps between UAVs and server.

## Installing dependencies

```sh
sh ~/drone_simulator_ws/src/multi_uav_map_construction/scripts/install/install_dependencies.sh
```

## Running the simulation

```sh
source ~/drone_simulator_ws/src/multi_uav_map_construction/scripts/start/simulation_test.sh <experimentId>
```
\<experimentId\>: is the experiment number, used to identify bag files.

-->

### User Instruction

A ROS package for Multi UAV Simulation in Gazebo simulator.

## Features
- Provide 3D simulation using Gazebo, ROS, MAVROS and PX4 firmware;
- Include a ROS Node to control each UAV use simple MAVROS commands;
- The UAV model was set up with a camera;
- It is possible to visualize the UAV camera in RVIZ;

## Installation
Following the steps above you are able to perform a simple setup of a Multi UAV simulation.

### Install ROS
For installation in Linux distribution, you should change the ROS distribution following these tutorials [here](http://wiki.ros.org/Installation).

### Install additional ROS Packages:
Run on terminal:
```sh
$ sudo apt install ros-kinetic-mavlink*
$ sudo apt install ros-kinetic-mavros*
$ wget https://raw.githubusercontent.com/mavlink/mavros/master/mavros/scripts/install_geographiclib_datasets.sh
$ sudo chmod +x install_geographiclib_datasets.sh
$ sudo ./install_geographiclib_datasets.sh
