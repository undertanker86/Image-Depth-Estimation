# Image-Depth-Estimation-Project

## Overview
This project implements an image depth estimation system using stereo matching techniques. It covers multiple methods, including pixel-wise matching, window-based matching, and an advanced approach using cosine similarity. The goal is to calculate disparity maps from stereo image pairs, which can be used to infer the depth of objects in a scene.

## Fetures
- **Pixel-wise Matching: Calculates disparity maps using pixel-level comparisons between stereo image pairs.
- **Window-based Matching: Enhances pixel-wise matching by considering neighboring pixels within a defined window.
- **Cosine Similarity Matching: Further improves the accuracy of disparity maps by treating windows as vectors and calculating cosine similarity between them.
  
## Requirements
- Python 3.8 or later
- Required Python packages:
- opencv-python
- numpy

## Installation
1. **Clone the Repository**:

   ```bash
    git clone https://github.com/undertanker86/Image-Depth-Estimation.git
    cd image-depth-estimation

## Result
The result in Aloe Datasets
![Alt text](https://img.upanh.tv/2024/08/20/ing2b6d7a0a46fe9dc61.png)
