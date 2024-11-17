# Image-Segmentation-Project
# Overview

This project implements an image segmentation tool using the Max Flow/Min Cut Theorem to separate foreground and background regions in grayscale images. The tool leverages graph-based optimization to deliver precise boundary detection and segmentation.

# Requirements

- **NumPy:** For efficient data manipulation and matrix operations.
- **Matplotlib:** For visualizing images and segmentation results.
- **Gurobi:** To solve the Max Flow/Min Cut optimization problem. You must have an active Gurobi license to rerun the code.

# Libraries required

  ```bash
  import gurobipy as gp
  import numpy as np
  import matplotlib.pyplot as plt
  import cv2
  ```
## Files Required
- [Pelican Image](pelican_picture.jpg): Main grayscale image used for segmentation.
- [Oval CSV](oval-1.csv): Contains pixel intensity data for the pelican image in CSV format, used for validating the segmentation algorithm.
- [Box CSV](box.csv): Another test dataset in CSV format, providing pixel intensity data to evaluate the tool’s performance on different images.

## Result
- [Segmentation Result](Final_Result_Pelican.png): This is the final result of the segmentation. The redoutline represents the segmentation boundary, computed using the Max Flow/Min Cut optimization technique.
