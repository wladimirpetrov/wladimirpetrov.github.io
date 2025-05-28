---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Vladimir Petrov**
Iowa City, USA
(319) 512-0066
v.petrov.18.02.94@gmail.com

Skills
======
* Robotics, Machine Learning (TensorFlow), Optimization, Motion Planning & Controls, Autonomous Navigation, Path Planning, SLAM, Multi-robot Coordination
* ML trained: Transformers, LSTM, RBFNN
* ROS & ROS2, C++ & Python, Simulink, MATLAB, Gazebo
* SolidWorks, Siemens NX + Teamcenter, Autodesk Inventor, ANSYS

Education
======
* **PhD Student in Mechanical Engineering**, Cooperative Autonomous Systems Lab, University of Iowa, Iowa City, USA (Winter 2023 – Present)
  * GPA: 3.95
* **Master of Engineering**, Volgograd State University, Volgograd, Russia (Fall 2010 – Summer 2015)
  * GPA: 3.96
  * Thesis: Development of Diesel Fuel System
  * Activities: Student Council, Local Charity Organization

Experience
======
* **Robotics Engineer Intern**, Mitsubishi Electric Research Laboratories (MERL), Cambridge, MA (Jan 2025 – Apr 2025)
  * Developed trajectory-generation and tracking algorithms for coordinated flights of multiple Crazyflie drones in constrained environments.
  * Utilized ROS2 and CrazySwarm2 for real-time communication and control.
  * Employed SLAM Toolbox for independent drone localization; merged 2D maps into full 3D point clouds.
  * Validated algorithms in RViz2 and co-authored a paper for upcoming publication.

* **Research Assistant**, Cooperative Autonomous Systems Lab, University of Iowa, Iowa City, USA (Winter 2023 – Present)
  * Implemented PID, LQR, MPC & NMPC, ML (TensorFlow & RBFNN), and L1 adaptive control on AUVs (Joubert BB2, BlueROV2, 690 AUV) and Crazyflie UAVs.
  * Trained ML algorithms: Transformers, LSTMs, RBFNNs for controls purposes.
  * Conducted trajectory optimization, path planning, obstacle avoidance, and SLAM experiments.
  * Built C++, Python, Gazebo, Simulink, and MATLAB workflows.
  * Publications: 
    * *Autopilot System for Depth and Pitch Control in AUVs: Navigating Near-Surface Waves and Disturbances*
    * *AUV Autopilot System for Controlling Depth and Pitch: Maneuvering Through Near-Surface Waves and Environmental Disturbances* 
    * Ongoing works on :
    	1) ML & TensorFlow Controls
    	2) MERL work on path planning
    	3) MPC BeBOT AUV

* **Chief of Mechanical Engineering Team**, Original-group PJSC, Moscow, Russia (Winter 2020 – Winter 2022)
  * Led R&D of Delta, Articulated, Cartesian, SCARA, and Polar robots.
  * Managed a team of 24 design engineers using Autodesk Inventor and Siemens NX.
  * Performed ANSYS simulations (motion, statics, dynamics, stress, deflection).

* **Mechanical Design Engineer**, Techprom LLC, Volzhsky, Russia (Spring 2018 – Summer 2019)
  * Designed Cartesian/Gantry and Delta robots in SolidWorks.
  * Ran simulations in ANSYS and SimulationX.

* **Mechanical Design Engineer**, Severstal-ropes PJSC, Volgograd, Russia (Spring 2016 – Spring 2018)
  * Developed Delta and Articulated robots in SolidWorks and Creo.
  * Simulated mechanical systems in SimulationX (motion, statics, dynamics, stress, deflection).

Honors & Awards
======
* Diploma with Honors, Volgograd State University (Summer 2015)

Publications
======
<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Talks
======
<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</ul>

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Service and Leadership
======
* Currently signed in to 43 different Slack teams

