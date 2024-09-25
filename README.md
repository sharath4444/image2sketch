# Image to Pencil Sketch Converter

This project is a Streamlit web application that converts an uploaded image into a pencil sketch using OpenCV. Users can upload images, view the original and the converted sketch side by side, and download both images. The application also checks if the uploaded image is already a sketch.

## Project Overview

The main goal of this project is to provide a simple and interactive interface for users to convert their images into pencil sketches. The application utilizes:
- **OpenCV**: For image processing, specifically for converting images to grayscale, applying Gaussian blur, and generating pencil sketches.
- **Streamlit**: For creating an easy-to-use web application interface that allows users to upload images and view results.

## Features
- Upload images in JPG or PNG format.
- Automatically converts the uploaded image to a pencil sketch.
- Displays the original image and the pencil sketch side by side.
- Download options for both the original image and the sketch.
- Warning message if the uploaded image appears to already be a sketch.
- Print functionality for the pencil sketch.

  ## deploy link
  ```bash
  https://image2sketch.streamlit.app/

## Prerequisites

Make sure you have Python installed on your system. You also need to install the following libraries:

```bash
pip install streamlit opencv-python pillow numpy
