# Construction-Dashboard
The application allows users to load an image and visualize it in 3D, by analyzing the intensity of pixels.

Components:
Main Application Class (ImageInterface):
Initializes the Tkinter GUI window and sets up the layout.
Contains methods for loading images, rendering them in 3D, displaying the image, marking points on the image canvas, and visualizing paths.

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
-Add a path finding algorithm that avoids obstacle(the walls)
-Add extra AI/ML models that can improve the safety of the construction workers and Help in improving EGS standards of companies.
PS: THIS DASHBOARD IS STILL UNDER CONSTRUCTION AND A THE PATH FINDING ALGORITHM IS STILL UNDER WORK.

