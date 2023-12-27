# Document_Warping_OpenCV
Using warping feature to detect documents and correct them for the viewer
## Overview

This mini project focuses on detecting documents in a video stream or image using computer vision techniques and applying a perspective transformation to obtain a flattened view of the document. The primary goal is to automate the process of identifying documents within a scene, even when the documents are tilted or skewed, and then rectify them to appear as if viewed from directly above.

## Features

- **Live Document Detection:** The project supports real-time document detection from a video stream, making it applicable for scenarios where documents are present in dynamic environments.

- **Perspective Transformation:** Once a document is detected, the program performs a perspective transformation to warp the document into a flat, top-down view, facilitating easier analysis or processing.

- **User Interaction:** Users can interact with the system by adjusting parameters such as video source, frame size, and contour area threshold to fine-tune the document detection process.

## Prerequisites

To run this project, ensure that you have the following prerequisites installed:

- Python 3.x
- OpenCV
- NumPy

## Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/Abdelghafour2001/Document_Warping_OpenCV.git
   cd Document_Warping_OpenCV
