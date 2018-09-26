# MultiRobot
Welcome to MultiRobot Simulation Platform!

About
==================
This is a simulation software platform which can be used for algorithm-oriented researchers in the area of multi-robot.
This software is developed using C# programming language with Visual Studio 2012 IDE.

Features
==================
This software includes two main features: Target Generation and Target Allocation.
1. Target Generation
Target generation is quite convenient to simulate the real scenes of multiple robots.
You can generate the point sets according to different requirements such as Random, Linear and so on.
The point sets can be saved into files as well as loaded for later research.
2. Target Allocation
Target Allocation is used to test different kinds of task allocation algorithm.
With the input of point sets and some configurations, the results of algorithm can be shown visually.
Also, the movement path of robots and some important parameters can be saved into files for later research.

Instruciton
==================
We have implemented some common task assignment algorithms.
In our paper, we compared the DAN method with other algorithms.
In order to reproduce our experimental results, please follow the steps.
1. Run the MAUV.exe which is in the 'Simulation Platform' directory.
2. In the 'Target Allocation' tab page, set some basic parameters in the 'Robot' sub tab page.
   Refer to config information in the 'configuration' directory for different cases.
3. Go to the 'Target Allocation' sub tab page, select a allocation method and load a point set.
4. Then click 'Route Generation' button to get the results of path visually.
5. Save the generated result, then you can review the result later through 'Show Route' sub tab page.
