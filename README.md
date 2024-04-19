# Construction-Dashboard
The application allows users to load an image, visualize it in 3D, mark two points on the image, and visualize a path between these points while avoiding obstacles detected by analyzing the intensity of pixels along the path.

Components:
Main Application Class (ImageInterface):
Initializes the Tkinter GUI window and sets up the layout.
Contains methods for loading images, rendering them in 3D, displaying the image, marking points on the image canvas, and visualizing paths.

Image Rendering and Visualization:
Renders the loaded image in 3D using Matplotlib.
Provides functionality to visualize a path between two points on the image.

Path Finding:
Implements a basic pathfinding algorithm (find_path) using a modified Rapidly-exploring Random Tree (RRT*) algorithm with obstacle avoidance.
Uses Bresenham's line algorithm to check for collisions with obstacles along the path.

Functionality:
Load Image: Allows users to select an image file (supports .png, .jpg, and .jpeg) and displays it in grayscale.
Visualize Path: Enables users to mark two points on the image and visualize the shortest path between them, avoiding obstacles represented by pixel intensities along the path.
3D Visualization: Renders the grayscale image in a 3D plot, where the x and y axes represent pixel coordinates, and the z-axis represents pixel intensity.

How to Use:
Run the script.
Click "Load Image" to select an image file.
Click on the image canvas to mark the start and end points.
Click "Visualize Path" to see the shortest path between the marked points, avoiding obstacles.

Notes:
The application assumes that lighter pixel intensities represent obstacles, while darker intensities represent clear paths. This assumption can be adjusted based on specific image characteristics.
The pathfinding algorithm and obstacle detection can be further optimized or replaced with more advanced techniques for real-world applications.

PS: THIS DASHBOARD IS STILL UNDER CONSTRUCTION AND A THE PATH FINDING ALGORITHM IS STILL UNDER WORK.

