# BeeProject_MiniRt

## Overview

A mini ray tracing project built in C using the MLX42 Library. Through miniRT, we learn the fundamentals and build a basic ray tracer that can render simple 3D scenes with objects such as, plane, cylinder and sphere.

## Core Features
- Parsing: Ensure the correct file and data are passed through the program, it will exit and return an error message when it parsed an invalid argument.
- Object and Scene: The program will parse ambient 'A', camera 'C', light 'L', sphere 'sp', plane 'pl' and cylinder 'cy'. Each of them will have their characteristics further checked and parsed. 
- Matrix Transformation: Using matrix to calculate translation, scaling and rotation of object and scene.
- Ray Intersection: Ray tracing algorithm is used to determine where the ray strike, shade, and reflective. The algorithm is from The Ray Tracer Challenge.
- Rendering: With all the info parsed and calculated, each pixel will be rendered and display on the screen. 

## Examples

## Sources:
- The Ray Tracer Challenge (http://raytracerchallenge.com)
