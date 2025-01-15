[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1n3133eyo1gseMYGoZueabw6FcHGUQZBC#scrollTo=WGHG7YxN2ARx)
# Two-Frame Based Magnification

This project implements a technique for image magnification using two frames to enhance the detail of a selected region in an image. The approach involves applying a magnification filter to a specific region of interest (ROI) in an image based on two frames—one original and one zoomed in—while maintaining the overall image structure.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Required Python packages:
  - `opencv-python`
  - `numpy`
  - `matplotlib`

You can install the required dependencies using the following command:

```bash
pip install opencv-python numpy matplotlib
Usage
Clone the repository or download the script file.

Open the script in your preferred Python environment.

Set the parameters such as:

Input image path.
Region of interest (ROI) coordinates (top-left corner and bottom-right corner).
Magnification factor.
Run the script. The program will:

Load the original image.
Magnify the specified region.
Replace the selected region with the magnified frame.
Output
The output will be an image where the selected region has been magnified based on the specified factor and seamlessly integrated into the original frame.
