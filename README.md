# CURVETOPIA: A Journey into the World of Curves Project

## Overview

This project focuses on detecting and completing curves in images using OpenCV and other image processing techniques. The main objectives are:

- **Detecting Symmetric Curves:** Identify and count symmetric curves in images.
- **Completing Incomplete Curves:** Use inpainting techniques to complete curves that are partially missing.

The project includes the following functionalities:
1. **Symmetric Curve Detection:** Identifies curves in images that exhibit horizontal or vertical symmetry.
2. **Curve Completion:** Uses inpainting to fill in incomplete curves in images.

## Features

- **Symmetric Curve Detection:**
  - Detects symmetric curves using edge detection and contour analysis.
  - Highlights symmetric curves in the output image.

- **Curve Completion:**
  - Completes curves using the inpainting technique.
  - Provides visualizations of the original image, mask, and completed curves.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- NumPy
- Google Colab or a local Python environment

### Usage

1. **Detect Symmetric Curves:**

   - Upload an image to Google Colab or place it in the project directory.
   - Run the `detect_symmetric_curves` function with the path to your image.

   ```python
   from your_module import detect_symmetric_curves

   image_path = "path/to/your/image.png"
   detect_symmetric_curves(image_path)
   ```

2. **Complete Incomplete Curves:**

   - Use the `complete_curves` function to fill in incomplete curves.

   ```python
   from your_module import complete_curves

   image_path = "path/to/your/image.png"
   complete_curves(image_path)
   ```

### Example

Here's an example of how to use the provided functions in Google Colab:

```python
import cv2
import numpy as np
from google.colab.patches import cv2_imshow

# Symmetric Curve Detection
def detect_symmetric_curves(image_path):
    # Function code here

# Curve Completion
def complete_curves(image_path):
    # Function code here

# Run symmetric curve detection
detect_symmetric_curves('/content/drive/MyDrive/art.png')

# Run curve completion
complete_curves('/content/drive/MyDrive/art.png')
```
##input

<img width="505" alt="image" src="https://github.com/user-attachments/assets/f75c32ab-db12-4d80-aede-f185336424db">

##input



### Results

- **Symmetric Curve Detection:** Outputs the number of symmetric curves and highlights them on the image.
- **Curve Completion:** Displays the original image, mask, and the inpainted image with completed curves.

## Contributing

Contributions are welcome! Please fork the repository, make changes, and submit a pull request. If you find any issues or have suggestions, feel free to open an issue.


## Acknowledgements

- OpenCV for image processing.
- NumPy for numerical operations.
