# Overview
This Folder is a collection of implementations for various traditional computer vision algorithms focused on object detection and feature detection. The goal of this project is to explore and compare classic methods for identifying key points, features, and objects within images using Python and OpenCV.


# Implemented Algorithms
 ## The following computer vision techniques have been implemented and are available in this repository:
 - Feature Detectors and Descriptors
 - FAST (Features from Accelerated Segment Test): A high-speed corner detection algorithm.
 - ORB (Oriented FAST and Rotated BRIEF): An efficient alternative to SIFT/SURF, combining the speed of FAST with the orientation component of BRIEF.
 - BRIEF (Binary Robust Independent Elementary Features): A feature descriptor that is very fast to compute and match, but needs a separate detector like FAST.
 - SIFT (Scale-Invariant Feature Transform): A robust algorithm for detecting and describing local features in images, invariant to scale and rotation.
 - SURF (Speeded Up Robust Features): Another robust feature detector and descriptor (note: usage may require special licensing depending on the environment).
 - HOG (Histogram of Oriented Gradients): A feature descriptor often used in conjunction with a classifier (like an SVM) for object detection, particularly for pedestrian detection.
