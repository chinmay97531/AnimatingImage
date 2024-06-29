# Cartoonifying an Image

The "Cartoonify an Image" project uses Python, OpenCV, and NumPy to transform real images into cartoon-like versions. The process starts by
reading the image and converting it to grayscale. Edge detection is performed using adaptive thresholding after applying a median blur to 
reduce noise. The original colored image undergoes bilateral filtering to smoothen it while preserving edges. Finally, the edge-detected 
image is combined with the smoothed color image, resulting in a cartoon-like effect. This project demonstrates the application of image 
processing techniques to achieve a creative transformation.
