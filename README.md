# Edge-Detection
Edge Detection using opencv-python

This project demonstrates the application of edge detection techniques on images using OpenCV and Python. Edge detection is a key technique in computer vision for detecting boundaries within an image, which is often the first step in identifying objects.

In this project, we utilize the following edge detection methods:

Canny Edge Detection: A multi-stage algorithm to detect a wide range of edges in images.
Laplacian Edge Detection: Based on second-order derivatives, useful for finding regions with rapid intensity changes.
Gaussian Blur: Applied before edge detection to reduce noise, improving the accuracy of the edge detection process.
Each step of the process, from loading and resizing the image to performing grayscale conversion, applying Gaussian blur, and detecting edges using both Canny and Laplacian methods, is visualized within the Jupyter Notebook.

### Steps Involved:
- Original Image Display: The input image is loaded and resized.
- Grayscale Conversion: The image is converted to grayscale, which simplifies the process of edge detection.
- Gaussian Blurring: The grayscale image is blurred to reduce noise and enhance edge detection.
- Canny Edge Detection: Edges are detected based on intensity gradients.
- Laplacian Edge Detection: Edges are detected using second-order derivatives.
All images are displayed within the Jupyter Notebook using matplotlib for ease of visualization.

