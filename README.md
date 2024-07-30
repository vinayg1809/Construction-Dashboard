# Construction-Dashboard
The application allows users to load an image and visualize it in 3D, by analyzing the intensity of pixels.

Components:
Main Application Class (ImageInterface):
Initializes the Tkinter GUI window and sets up the layout.
Contains methods for loading images, rendering them in 3D, displaying the image.

Image Rendering and Visualization:
Renders the loaded image in 3D using Matplotlib.
Provides functionality to visualize a path between two points on the image.

Functionality:
Load Image: Allows users to select an image file (supports .png, .jpg, and .jpeg) and displays it in grayscale.
3D Visualization: Renders the grayscale image in a 3D plot, where the x and y axes represent pixel coordinates, and the z-axis represents pixel intensity.

How to Use:
Run the script.
Click "Load Image" to select an image file.

Notes/ extra additions:
-Add a path finding algorithm that avoids obstacle(the walls) and updates the location of tehe worker's at short intervals of time.

-Creation of a NN that uses the Gyroscopic data and tell's us if the worker is free-falling or stationary .

-Using the data the NN  has provided we can mark the potential hazardous spots on the 3D map.

-Using Digital Twin for updating the 3D model real time by using sensors and making a YOLO model to compare and update.

PS: THIS DASHBOARD IS STILL UNDER CONSTRUCTION AND A THE PATH FINDING ALGORITHM IS STILL UNDER WORK.

