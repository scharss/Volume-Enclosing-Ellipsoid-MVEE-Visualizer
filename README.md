# Interactive 3D Minimum Volume Enclosing Ellipsoid (MVEE) Visualizer 🌌

![MVEE Visualizer](https://raw.githubusercontent.com/scharss/Volume-Enclosing-Ellipsoid-MVEE-Visualizer/refs/heads/main/3dcil.png)

This web application provides an interactive, real-time visualization of the Minimum Volume Enclosing Ellipsoid (MVEE) algorithm in a 3D space. It is built entirely with web technologies: [Three.js](https://threejs.org/) for 3D rendering and [numeric.js](http://numericjs.com/) for the underlying linear algebra computations.

The MVEE is a fundamental concept in computational geometry and data analysis. It is the smallest possible ellipsoid that contains a given set of points. This tool allows users to intuitively understand how the shape, orientation, and size of the MVEE adapt to the spatial distribution of a point cloud.

## What does this application do? 🧐

This tool allows you to:

*   🎨 Interactively build 3D point clouds from scratch.
*   ✨ Visualize the smallest possible ellipsoid that encloses your data in real-time.
*   🔬 Explore the shape, size, and orientation of different data groups.
*   🔄 Compare the overlap and separation between distinct point clouds.

It serves as an excellent educational tool for concepts in computational geometry, data clustering, and outlier detection.

## How to Use It 🚀

The application has two main modes: **Explore Mode** and **Paint Mode**.

### 1. Explore Mode (Default) 🌍

This is the default mode when the application loads. Use your mouse to freely navigate the 3D scene:

*   **Left-click + Drag:** Rotate the camera around the data.
*   **Mouse Wheel:** Zoom in and out.
*   **Right-click + Drag:** Pan the camera.

### 2. Paint Mode (Creation) 🖌️

To create your own data:

1.  Click the "**Activate Brush**" button. The cursor will change to a crosshair, and camera controls will be temporarily disabled.
2.  **Click and drag** your mouse across the grid plane to "paint" a 3D point cloud for the selected group.
3.  When you release the mouse, the MVEE for the points you just created will be automatically calculated and rendered.
4.  Click "**Deactivate Brush**" to return to Explore Mode.

## Other Controls ⚙️

*   **Active Group:** Use the radio buttons in the "Controls" panel to select which group (Group A, Group B, or Group C) you want to add points to.
*   **Load Example:** Click this button to load a pre-generated simulation with multiple point clouds and their corresponding MVEEs.
*   **Reset:** Click this button to completely clear the scene and start over.
