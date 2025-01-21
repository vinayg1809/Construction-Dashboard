# Construction-Dashboard  

The **Construction-Dashboard** is a tool designed to load an image and visualize it in 3D by analyzing the intensity of pixels. The application provides a robust platform for enhancing site safety and monitoring by incorporating advanced features like pathfinding and real-time updates.

---

## Features  

### **Core Components**  
1. **Main Application Class (`ImageInterface`)**  
   - Initializes the Tkinter GUI window and sets up the layout.  
   - Provides functionality for loading images, rendering them in 3D, and displaying the image.  

2. **Image Rendering and Visualization**  
   - Renders the loaded image in 3D using Matplotlib.  
   - Visualizes paths between two points on the image.  

### **Functionality**  
- **Load Image**:  
   - Allows users to select an image file (supports `.png`, `.jpg`, and `.jpeg`).  
   - Displays the selected image in grayscale.  
- **3D Visualization**:  
   - Renders the grayscale image in a 3D plot.  
   - The x and y axes represent pixel coordinates, while the z-axis represents pixel intensity.  

---

## How to Use  

1. Run the script.  
2. Click **"Load Image"** to select an image file.  
3. Visualize the loaded image in both 2D and 3D.  

---

## Future Enhancements  

### 1. **Pathfinding Algorithm**  
   - Implement a pathfinding algorithm to avoid obstacles (e.g., walls) and dynamically update worker locations at regular intervals.  

### 2. **Neural Network (NN) for Worker Safety**  
   - Develop a neural network to process gyroscopic data and determine if a worker is **free-falling** or **stationary**.  
   - Mark hazardous spots on the 3D map using NN insights.  

### 3. **Digital Twin Integration**  
   - Leverage sensor data to update the 3D model in real time.  
   - Train a YOLO model to compare actual site conditions with the 3D visualization for more accurate updates.  

---

## Notes  

- This dashboard is **still under construction**.  
- The **pathfinding algorithm** is currently in development.  
