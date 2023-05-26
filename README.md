This repository contains code for performing Canny edge detection on a road image using OpenCV (cv2) library in Python. The code also overlays the detected edges on the original image to provide a visual representation of the edges.

The main steps of the code include:

Importing the necessary libraries: cv2 for image processing, numpy for numerical operations, and matplotlib.pyplot for visualizations.
Defining the path to the road image file and reading the image using cv2.imread().
Preprocessing the image by converting it to grayscale using cv2.cvtColor() and applying Gaussian blur using cv2.GaussianBlur() to reduce noise.
Applying the Canny edge detection algorithm to the blurred image using cv2.Canny() with specified threshold values.
Creating an overlay image by copying the original image and setting the pixels corresponding to the detected edges to green.
Creating a blended image by combining the original image and the overlay image using cv2.addWeighted(). The alpha parameter controls the transparency of the overlay.
Creating a figure with two subplots using plt.subplots(). Displaying the original image in the first subplot and the blended image with the overlayed edges in the second subplot.
Adding titles to the subplots, turning off the axes, and adjusting the spacing between the subplots.
Displaying the figure using plt.show().
This repository serves as a useful resource for anyone interested in understanding and implementing Canny edge detection on images using OpenCV. The code provides a clear demonstration of the steps involved in detecting edges and overlaying them on the original image,
which can be helpful for various applications such as road detection and object recognition.
