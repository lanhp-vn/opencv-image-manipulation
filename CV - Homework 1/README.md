# OpenCV Image Manipulation

Computer Vision Homework 1 - Image manipulation tasks using OpenCV and Python.

## Overview

This project implements basic image processing operations including color channel manipulation, pixel operations, and geometric transformations on a sample red object image.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib

## Tasks Implemented

### Question 1: Color Image Operations
- **a.** Swap red and blue color channels
- **b.** Extract blue channel as grayscale (Ablue.jpg)
- **c.** Extract red channel as grayscale (Ared.jpg)
- **d.** Channel selection for object detection analysis

### Question 2: Pixel Manipulation
- Extract 50x100 pixel region from blue channel image
- Insert extracted region into corresponding position of red channel image

### Question 3: Arithmetic and Geometric Operations
- **a.** Calculate min, max, mean, and standard deviation of grayscale image
- **b.** Normalize image using statistical operations
- **c.** Apply 5-pixel left translation using `warpAffine`
- **d.** Compute absolute difference between original and shifted images

## Files

- `main.ipynb` - Main Jupyter notebook with complete implementation
- `sample_image.jpeg` - Input image of red object
- `requirements.pdf` - Assignment specifications
- `Ablue.jpg` - Blue channel grayscale output
- `Ared.jpg` - Red channel grayscale output

## Usage

Open and run `main.ipynb` in Jupyter Notebook to execute all image processing tasks.

## Results

The notebook demonstrates fundamental OpenCV operations for color space manipulation, statistical analysis, and geometric transformations on digital images.