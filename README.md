# Object Detection for Cleaning robot
For target detection requirements of sweeping robots,a benchmark dataset (ODSR-IHS) in an indoor house scenario is used with images at a specific angle( from sweeping robots).
The dataset was made to validate and develop data-driven object detection methods, and laid the foundation for the optimization of the target detection model for sweeping robots.
A single shot detection (SSD) algorithm called You Only Look Once “YOLO” is used. It is a cutting-edge detection algorithm that can identify distinct objects within the space of an image. It looks at the image once, divides it into grid cells, which are responsible for predicting bounding boxes, and output a score known as the Intersection Over Union (IOU). 
The image processing was done with OpenCV and the processed images were used to train the last fully connected layers of the network using Python’s Keras package with Darknet and Tensorflow as backends.
Transfer learning was used to reduce computational cost, improve how the model generalizes and makes it more robust. 
