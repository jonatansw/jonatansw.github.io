---
title: "Online 3-Dimensional Path Planning with Kinematic Constraints in Unknown Environments Using Hybrid A* with Tree Pruning"
collection: publications
permalink: https://www.mdpi.com/1424-8220/21/4/1152
excerpt: ''
date: 2021-02-06
venue: 'Sensors Special Issue on Intelligence and Autonomy for Underwater Robotic Vehicles'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Scharff Willners, J.; Gonzalez-Adell, D.; Hernández, J.D.; Pairet, È.; Petillot, Y. Online 3-Dimensional Path Planning with Kinematic Constraints in Unknown Environments Using Hybrid A* with Tree Pruning. <i>Sensors</i> 2021, 21, 1152. https://doi.org/10.3390/s21041152'
---
In this paper we present an extension to the hybrid A* (HA*) path planner. This extension allows autonomous underwater vehicles (AUVs) to plan paths in 3-dimensional (3D) environments. The proposed approach enables the robot to operate in a safe manner by accounting for the vehicle’s motion constraints, thus avoiding collisions and ensuring that the calculated paths are feasible. Secondly, we propose an improvement for operations in unexplored or partially known environments by endowing the planner with a tree pruning procedure, which maintains a valid and feasible search- tree during operation. When the robot senses new obstacles in the environment that invalidate its current path, the planner prunes the tree of branches which collides with the environment. The path planning algorithm is then initialised with the pruned tree, enabling it to find a solution in a lower time than replanning from scratch. We present results obtained through simulation which show that HA* performs better in known underwater environments than compared algorithms in regards to planning time, path length and success rate. For unknown environments, we show that the tree pruning procedure reduces the total planning time needed in a variety of environments compared to running the full planning algorithm during replanning.

[Download paper here](http://jonatansw.github.io/files/papers/sensors-21-01152.pdf)

![alt text](http://jonatansw.github.io/files/papers/images/ha.png "Algorithm reusing prior explored search tree during replanning")

