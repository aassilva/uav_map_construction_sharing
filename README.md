# A Map Construction and Sharing Framework


**ABSTRACT &mdash;** With the popularity of Unmanned Aerial Vehicles (UAVs), there is an increasing demand for autonomous navigation applications, which require the use of high-definition mapping techniques of the environments. However, in highly dynamic environments, maps need to be updated regularly, which has an impact on the path planning algorithms used by the autonomous navigation system. A deterministic energy-efficient solution for a straightforward path in the path planning is computationally exhaustive. To overcome this limitation, recent solutions based on edge computing aim to provide safe and energy-efficient solutions to assist UAVs in autonomous navigation. This paper proposes an energy-efficient map building and sharing framework for multiple UAV systems. The proposed system uses edge servers to merge a global map that incorporates all Simultaneous Localization and Mapping updates, providing UAVs with consistent maps that are efficiently updated. The proposed system is evaluated and tested in laboratory, and field experiments. The field tests revealed that the object detection and classification model obtained a median efficiency rate of around 95%, even with a median packet loss rate between 25% and 35%. For the benefit of the community, we make public the source code.


The hardware architecture used in this work is available in the folder:
>[uav_map_construction_sharing/mult_uav/](https://github.com/aassilva/uav_map_construction_sharing/tree/main/mult_uav)

Figure below summarizes the main components of the system architecture developed for UAVs.

![Figure 1](https://github.com/aassilva/uav_map_construction_sharing/blob/main/docs/system_architecture.png)

---

On the edge server a software package is implemented is made available in the folder: 
>[uav_map_construction_sharing/sever/](https://github.com/aassilva/uav_map_construction_sharing/tree/main/sever)

Figure below presents an overview of the process performed by the server.

![Figure 2](https://github.com/aassilva/uav_map_construction_sharing/blob/main/docs/server_achitecture.png)
