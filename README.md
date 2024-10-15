# BeeProject_MiniRt


## Overview
A mini ray tracing project built in C using the MLX42 Library. Through miniRT, we learn the fundamentals and build a basic ray tracer that can render simple 3D scenes with objects such as, plane, cylinder and sphere. This was a group project and I worked on with the amazing and organized Lumi_K(https://github.com/lkilpela).

## Core Features
- Parsing: Ensure the correct file and data are passed through the program, it will exit and return an error message when it parsed an invalid argument.
- Object and Scene: The program will parse ambient 'A', camera 'C', light 'L', sphere 'sp', plane 'pl' and cylinder 'cy'. Each of them will have their characteristics further checked and parsed. 
- Matrix Transformation: Using matrix to calculate translation, scaling and rotation of object and scene.
- Ray Intersection: Ray tracing algorithm is used to determine where the ray strike, shade, and reflective. The algorithm is from The Ray Tracer Challenge.
- Rendering: With all the info parsed and calculated, each pixel will be rendered and display on the screen. 

## Examples
<h1></h1>
Example 1
<div align="left">
  <img src="./images/sphere.png" style="width: 50%">
Sphere with no background
</div>
Example 2
<div align="left">
  <img src="./images/mickey.png" style="width: 50%">
Multiple object plus spheres to form a Mickey shape with plane as background
</div>div

## Sources:
- The Ray Tracer Challenge (http://raytracerchallenge.com)
