# kai
Python based image data-set creator for hand models and corresponding depth maps in stereo configuration in Blender 3D.
This project contains Python + Blender source files for <b>creating data sets of hand models mainly rendered images and their corresponding depth maps.</b>
Blender is a free and open source 3D platform. It supports 3D modeling and rendering as well as many advanced features like animation, simulation, compositing, motion tracking, video editing and game creation. I use the python scripting capacity to create an auto image dataset generator. 

# Overview
The project has a blender file which is already rigged with bones similar to a human hand.
The environment maps can be set programatically. The default is a studio scene.
There are two hand models each for the right and left hands whose bones ends with .R or .L respectively.
The bones are configured such that the rotation is limited to mimic that of a real human hand.
The idea is to have a framework for creating large number of datasets from the camera and the depth images for the training of artificial neural networks for hand tracking.
The python will also give the key bones' location in a ".loc" file along with the depth map and the rendered image for each render.

# Dependencies


# Getting Started

# License
MIT license
