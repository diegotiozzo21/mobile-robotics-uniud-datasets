# mobile-robotics-uniud-datasets
This repository contains datasets collected using AgileX mobile robots in different scenarios. 

## Sensors specifications

**LiDAR sensor**: Velodyne VLP16 (Puck) [datasheet](./datasheet/velodyne.pdf)

**9-Axis IMU**: Xsens MTi 630 [datasheet](./datasheet/MTi-630.pdf)

**GNSS receiver**: Ardusimple simpleRTK2B Budget [datasheet](https://www.ardusimple.com/simplertk2b-hookup-guide/)

**Info**: The following information applies to everything below unless otherwise stated! The Velodyne LiDAR sensor range is set to 100 m and LiDAR point clouds are published at 10 Hz in the topic *velodyne_points*. The IMU sensor reference frame is considered coincident with the LiDAR sensor reference frame, i.e., the $x$ axis points forward and the $z$ axis points upward. The magnetometer reports the pose of the robot with respect to a fixed ENU reference frame (i.e., $x$ axis points to the East, $y$ axis points to the North, and $z$ axis points up). IMU data are published at 200 Hz in the topic */imu/data*. GNSS data are published at 1 Hz in the topic */ublox_position_receiver/fix*. 

-----

## Uniud Rizzi campus - Single corridor/Squared plant

**Mobile robot**: AgileX Scout Mini

**Mobile platform specifications**: https://docs.trossenrobotics.com/agilex_scout_mini_docs/specifications.html

<img src="img/single_corridor.jpg" width="400" />

### Single corridor
**Download dataset at**: [download_link](https://uniudamce-my.sharepoint.com/:u:/g/personal/diego_tiozzo_uniud_it/EbvGEXrWFihMlHSk3xHcQRwBXyPgFy4TIit5rChXjifMvw?e=Wb9pfU)

### Squared plant 
**Download dataset at**: [download_link](https://uniudamce-my.sharepoint.com/:u:/g/personal/diego_tiozzo_uniud_it/EXaexaymhVVDlyMibmMuPGoBpMj-5L6y5YDryUugMQBj6A?e=AlItvO)

Relevant topics list: 
```
/imu/data
/velodyne_points
```

Thank you for citing [Tiozzo Fasiolo, D et al. (2023)]([./config/doc/paper.pdf](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/D5B49F3F7FC0992EE0CA3A6DD85BAAB8/S026357472300053Xa.pdf/comparing_lidar_and_imubased_slam_approaches_for_3d_robotic_mapping.pdf)) if you use any of this data.
```
@article{fasiolo2023comparing,
  title={Comparing LiDAR and IMU-based SLAM approaches for 3D robotic mapping},
  author={Fasiolo, Diego Tiozzo and Scalera, Lorenzo and Maset, Eleonora},
  journal={Robotica},
  pages={1--17},
  year={2023},
  publisher={Cambridge University Press}
}
```

-----

## Uniud Rizzi campus - Courtyard 

**Mobile robot**: AgileX Scout 2.0

**Mobile platform specifications**: https://docs.trossenrobotics.com/agilex_scout_20_docs/specifications.html

<img src="img/courtyard.jpg" width="400" />

**Download dataset at**: 

Relevant topics list: 
```
/imu/data
/velodyne_points
```

Thank you for citing [Tiozzo Fasiolo, D et al. (2023)]([./config/doc/paper.pdf](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/D5B49F3F7FC0992EE0CA3A6DD85BAAB8/S026357472300053Xa.pdf/comparing_lidar_and_imubased_slam_approaches_for_3d_robotic_mapping.pdf)) if you use any of this data.
```
@article{fasiolo2023comparing,
  title={Comparing LiDAR and IMU-based SLAM approaches for 3D robotic mapping},
  author={Fasiolo, Diego Tiozzo and Scalera, Lorenzo and Maset, Eleonora},
  journal={Robotica},
  pages={1--17},
  year={2023},
  publisher={Cambridge University Press}
}
```

-----

## LabVillage - Parking lot full/Parking lot SMACT3

**Mobile robot**: AgileX Bunker

**Mobile platform specifications**: https://docs.trossenrobotics.com/agilex_bunker_docs/specifications.html

<img src="img/labvillage.jpg" width="400" />

Topics list: 
```
\velodyne_points
```

**Info**: 

## Servadei vineyard 2022 - June/July/December

**Mobile robot**: AgileX Scout 2.0

**Mobile platform specifications**: https://docs.trossenrobotics.com/agilex_scout_20_docs/specifications.html

<img src="img/servadei2022.jpg" width="400" />

**Info**: 

-----




