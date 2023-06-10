# FCND
Udacity flying car and autonomous flight engineer nano-degree program.

## 01. Introduction to Autonomous Flight
### Welcome
- Dronecode's [opensource UAV platform](https://www.dronecode.org/projects/).
- https://www.youtube.com/watch?v=kuNEtnVnTGE
- https://www.youtube.com/watch?v=w6bP7l2o81s
- https://www.youtube.com/watch?v=ZUYHuAa9xfo
- Projects - https://youtu.be/xq0gZBySFOo
- Astounding Flying Machines - https://www.ted.com/talks/raffaello_d_andrea_the_astounding_athletic_power_of_quadcopters

### Autonomous Flight
- Overview - https://youtu.be/5P90uJyUg8c
- History of Autonomous Flight - https://youtu.be/z1BHCF7nSEQ
- Vehicle Morphologies - https://youtu.be/ojMfOPp_SfY
- Why Quadrotors? - https://youtu.be/ao5boE0jJpE
- Quadrotors Components - https://youtu.be/BjVAmh3396g
- Airframe - https://youtu.be/nRChl_1OrZ0
- Motors/ Speed Controllers - https://youtu.be/TARVT5XBRCc
  - https://www.quantumdev.com/brushless-motors-vs-brush-motors-whats-the-difference/
  - https://www.electronicdesign.com/technologies/components/electromechanical/article/21796048/electronic-design-whats-the-difference-between-brush-dc-and-brushless-dc-motors
  - https://en.wikipedia.org/wiki/Electronic_speed_control
  - https://www.youtube.com/watch?v=OZNxbxL7cdc
- Propellers - https://youtu.be/tP67LXN60ZA
- Batteries - https://youtu.be/P7NQklPq7xI
- Driving a Quad - https://youtu.be/QaLhiaXFdA0
- Attitude Control - https://youtu.be/qxjGln_eA28
- Autopilot - https://youtu.be/X9_1osn1L7A
- IMU Gyros - https://youtu.be/TDus6cfGvRw
- IMU Accelerometers - https://youtu.be/1ccatHUDjDA
- GPS - https://youtu.be/1g_MxNlFTnQ
- Flight Computer - https://youtu.be/xBQzqUfz24s
- Summary - https://youtu.be/LsF0SRZZvhE

### Backyard Flyer
- Lesson Introduction - https://youtu.be/z48qy6lGU5M
- Lesson Overview - https://youtu.be/wIRJPPH2gkc
- Simulator Demonstration - https://youtu.be/8zpkGojsw6g
- Simulator Exploration - Manual Flight - https://github.com/udacity/FCND-Simulator-Releases/releases
- Flight Computer Programming - https://youtu.be/8TFLgWGyfrg
- Environment Setup - https://github.com/udacity/FCND-Term1-Starter-Kit.git
- Simulator Exploration - Programmatic Flight - https://github.com/udacity/udacidrone
- The Problems with Sequential Execution - https://youtu.be/TCz0PkLoxgU
- Event Driven Programming Explained - https://youtu.be/f_GPA9ULqJU
- A Simple Flight Plan - https://youtu.be/Lq4DmvlsJAI 
- Phases of Flight - https://youtu.be/IZjLJxSYdRM

### Drone Integration
- Intel Aero Unboxing - https://youtu.be/_4r9ghv6Mm8
- Intel Aero First Boost - https://youtu.be/jXKZwWdhLpA
  - Flight modes - https://youtu.be/CemgWroChSE
  - The Remote Control - https://youtu.be/_Ei05vGbttg
- A Note on Safety - https://youtu.be/4-9CidAXkNI
  - Know Before You Fly - https://knowbeforeyoufly.org/home
  - Registering your drone - https://www.faa.gov/uas/getting_started
  - Part 107 - https://www.faa.gov/uas/commercial_operators/part_107_airspace_authorizations
  - Drone Regulation - https://youtu.be/gKulshbx8J0
  - Community guidelines - https://www.modelaircraft.org/system/files/documents/105.pdf
- Intel Aero Setup - https://youtu.be/TNoqm87Yd6c
  - https://github.com/intel-aero/meta-intel-aero/wiki/08-Aero-Network-and-System-Administration
  - https://github.com/intel-aero/meta-intel-aero/wiki/02-Initial-Setup
  - https://github.com/intel-aero/meta-intel-aero/wiki
- Getting Familiar with QGroundControl - https://youtu.be/z4_m_IIek-Q
- Configure PX4 - https://youtu.be/q2S4JOSX9wA
  - https://docs.px4.io/main/en/ros/offboard_control.html
- Modifying Backyard Flyer - https://udacity.github.io/udacidrone/docs/connection-api.html
- Let's go Fly - https://youtu.be/XPH-WR0i-Xs
- Crazyflie Introduction - https://www.bitcraze.io/documentation/tutorials/getting-started-with-crazyflie-2-x/
- Crazyflie Keyboard Control - https://github.com/bitcraze/crazyflie-lib-python


## 02. Planning
### Planning as Search
- Sebastian Introduction - https://youtu.be/2s3Pxc6AS8Y
- Transition to Planning - https://youtu.be/0nyCrWuO1QM
- The Planning Problem - https://youtu.be/oyPT3qirXPk
- Search Space - https://youtu.be/vsMQtkOjT3c
- Grid Representation - https://youtu.be/WcC-CfvQuJI
- Search - https://youtu.be/_iJ_pPZcLJc
- Partial Plans - https://youtu.be/zcuT9e4TgKo
- Breadth vs Depth - https://youtu.be/mtBKgqxjCyQ
  - Breadth-First Search - always expands shortest plan first
  - finds the shortest path to goal
  - computationally intensive
  - Depth first - expands last successful
  - requires a bit of luck
  - can fail completely
- Breadth-First Search Exercise - Jupyter Notebook - [BFS](./02_Planning/01_10_Breadth-First_Exercise/BFS.ipynb)
- Cost - https://youtu.be/qEYbn-jq7Qg
- Cost Exercise - Jupyter Notebook - [Cost](./02_Planning/01_12_Cost_Exercise/Cost.ipynb)
- Heuristics - https://youtu.be/qBAwN2r573Q
- A* - https://youtu.be/yT-8YRxSkqk
- A* Exercise - Jupyter Notebook - [A-Star](./02_Planning/01_15_A-Star_Exercise/A-Star.ipynb)
- Summary - https://youtu.be/MlvfEd8REJI

### Flying Car Representation
- Sebastian Introduction - https://youtu.be/54bXmWz_U7k
- Introduction - https://youtu.be/PsHOHInwDIk
- Geodetic Frame - https://youtu.be/CwA1L8uJ71I
- ECEF (Earth Center Earth Fixed) Frame - (NED - North East Down Frame)- https://youtu.be/9e3Gl-b_rvw
  - Right hand cartesian co-ordinates
- Geodetic to NED Exercise - Jupyter notebook - [Geodetic to NED Exercise](./02_Planning/02_05_Geodetic_to_NED/Geodetic%20to%20NED.ipynb)
  - https://pypi.org/project/utm/
  - https://en.wikipedia.org/wiki/Universal_Transverse_Mercator_coordinate_system
- Body Frame - https://youtu.be/JEDZyWtco5k
  - It is important for knowing the locations of the sensors on the body of the vehicle for sensor fusion.
  - This is the best cooridnate frame for representing control inputs such as velocities and accelerations.
- Eulers angles - https://youtu.be/C5bRTJ9UGgA
  - roll - counter clockwise positive - X axis
  - pitch - counter clockwise positive - Y axis
  - yaw - counter clockwise positive - Z axis
- Gimbal Lock - https://youtu.be/gWL0oXWADSU
  - 3 Axis Gimbal Simulator - https://github.com/udacity/FCND-Gimbal-Demo/releases/tag/v1.0
- Rotation Matrices - https://youtu.be/sUoaCP9S9V8
  - Rotations in Three Dimensions: Euler Angles and Rotation Matrices - https://danceswithcode.net/engineeringnotes/rotations_in_3d/rotations_in_3d_part1.html
  - Jupyter Notebook - [Rotations](./02_Planning/02_10_Euler_Rotations_Exercise/Rotations.ipynb)
- Quaternions - https://youtu.be/Jwelviv1ZNY
- Quarternion Exercise
  - https://youtu.be/SZXHoWwBcDc
  - Jupyter Notebook - [Quaternions](./02_Planning/02_12_Quarternion_Exercise/Quaternions.ipynb)
- Motions as Transformations - https://youtu.be/1Lp4eNjhwxs
- Configuration space - https://youtu.be/a08D9WnuRHU
  - https://www.youtube.com/watch?v=SBFwgR4K1Gk
- Configuration Space Exercise - Jupyter Notebook - [Configuration-Space](./02_Planning/02_15_Configuration_Space_Exercise/Configuration-Space.ipynb)
- Summary - https://youtu.be/iXzj0F2zhKk
  - https://mzucker.github.io/swarthmore/

### From Grids to Graph
- Sebastian Introduction - https://youtu.be/MYtJg8fe4U4
- Introduction to Graphs - https://youtu.be/ikh_CDbMwec
- Waypoint Extraction - https://youtu.be/rI5AJGHStxA
- Collinearity - https://youtu.be/NsmiEpZKYJU
- Collinearity Exercise - Jupyter Notebook - [Collinearity](./02_Planning/03_05_collinearity_exercise/Collinearity.ipynb)
- Ray Tracing - https://youtu.be/BiPdcTmi5Yg
- Bresenham - https://youtu.be/DhLZnsJxd-E
- Bresenham Exercise - Jupyter Notebook - [Bresensham](./02_Planning/03_08_bresenham_exercise/Bresenham.ipynb)
- Putting it all together - Jupyter Notebook - [A-Star-City](./02_Planning/03_09_putting_it_together/A-Star-City.ipynb)
- Grids to Graphs - https://youtu.be/DDamvBxXP3I
- Graph Tradeoffs - https://youtu.be/gQvoAaAYP88
- Generating Graphs - https://youtu.be/Pj1U6VHs1w4
- Medial Axis - Jupyter Notebook - [Medial-Axis](./02_Planning/03_13_Medial_axis_exercise/Medial-Axis.ipynb)
- Voronoi Graph Exercise 
  - SciPy Library - https://scipy.org/
  - Voronoi Method - https://docs.scipy.org/doc/scipy-0.18.1/reference/generated/scipy.spatial.Voronoi.html
  - Jupyter Notebook - [Voronoi Graphs](./02_Planning/03_14_Vornoi_Graph_Exercise/Voronoi.ipynb)
- Graph Search Exercise
  - Jupyter Notebook - [Graph-Search](03_15_Graph_Search_Exercise/Graph-Search.ipynb)
  - NetworkX package - https://networkx.org/ 
- Deadbands - https://youtu.be/kswcczWbszA
- Summary - https://youtu.be/RGkoXva9rSc

### Moving in to 3D
- Sebastian Introduction - https://youtu.be/41DhFrk6m7s
- Introduction - https://youtu.be/x7aDcy9xxrQ
- 3D Grids - https://youtu.be/SzNLVvlvOvs
- Voxel Map Exercise
  - Jupyter Notebook - [Voxel-Map](./02_Planning/04_04_Voxel_Map_Exercise/Voxel-Map.ipynb)
- 2.5D Maps - https://youtu.be/oWvl2yaoblY
- Random Sampling - https://youtu.be/DtmF5xOx2P0
- Random Sampling Exercise
    - Shapely - https://shapely.readthedocs.io/en/stable/manual.html
    - Jupyter Notebook - [Random-Sampling](./02_Planning/04_07_Random_Sampling_Exercise/Random-Sampling.ipynb)
- Probabilistic Roadmap - https://youtu.be/DCSe-uBfBNY
- Probablistic Roadmap Exercise
  - KD Tree - https://en.wikipedia.org/wiki/K-d_tree
  - The Big O Notation - https://robbell.io/2009/06/a-beginners-guide-to-big-o-notation
  - Shapely - https://shapely.readthedocs.io/en/stable/manual.html
  - Scikit-learn - https://scikit-learn.org/stable/
  - scikit-leanr KD tree - https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KDTree.html
  - Jupyter Notebook - [Probabilistic-Roadmap](./02_Planning/04_09_Probabilistic_Roadmap_Exercise/Probabilistic-Roadmap.ipynb)
- Local Planning - https://youtu.be/DsUE1rYvRyw
- Receding Horizon - https://youtu.be/-wTe_AFFT-I
- Receding Horizon Exercise
  - Jupyter Notebook - [Receding-Horizon](./02_Planning/04_12_Receding_Horizon_Exercise/Receding-Horizon.ipynb)
- Replanning - https://youtu.be/zcZbKZJ3D6s
- Summary - https://youtu.be/ydWkeSB30zs
  
### Real World Planning
### Project: 3D Motion Planning
- Sebastian Introduction - https://youtu.be/0ChnDlwpeBw
- Project Intro - https://youtu.be/hR__HI_Ocew
- Worspace Intro - 
- 3D Motion Planning -

## 03. Controls
### Vehicle Dynamics
### Introduction to Vehicle Control
### Control Architecture
### Full 3D Control
### Project: Building a Controller
### Drone Integration

## 04. Estimation
### Introduction to Estimation
### Introduction to Sensors
### Extended Kalman Filter
### The 3D EKF and UKF
### Project: Estimation
### GPS Denied Navigation

## 05. Fixed Wing
### Introduction to Fixed-Wing Flight
### Lift and Drag
### Longitudinal Model
### Lateral-Directional Model
### Fixed-Wing Autopilot
### Optional Project: Fixed Wing Control