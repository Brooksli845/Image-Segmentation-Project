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