# Adobe-GenSolve : CURVETOPIA: A Journey into the World of Curves


Curvetopia is a Python-based project focused on the identification, regularization, and beautification of 2D curves derived from line art. The project involves processing line art represented as polylines, regularizing these curves into geometric shapes, exploring symmetry, and completing any incomplete curves. The final outputs are saved as SVG files, which can also be rasterized into PNG images.

# Dataset 
We have used the following dataset : https://www.kaggle.com/datasets/ashishjangra27/doodle-dataset

# Implementation 
To start processing the polylines, use the following steps:

__1. Load and Visualize Data:__
- Load the CSV file containing the polylines.
- Visualize the line art using the provided plot function.

__2. Regularize Curves:__
- Implement geometric analysis to identify specific shapes within the polylines, such as straight lines, circles, ellipses, rectangles, etc.

__3. Explore Symmetry:__
- Analyze the curves to detect reflective symmetries in closed curves.

__4. Complete Incomplete Curves:__
- Apply computer vision techniques to complete any gaps in the curves.

__5. Convert to SVG and Rasterize:__
- Convert the processed polylines to SVG files and optionally rasterize them to PNG format.

# Features

- Polyline Processing: Load and visualize polylines from CSV files.
- Curve Regularization: Identify and regularize common geometric shapes within the polylines.
- Symmetry Exploration: Detect reflective symmetries in closed curves.
- Curve Completion: Complete incomplete curves to create a smooth and continuous line.
- SVG & PNG Export: Save the processed curves as SVG files and rasterize them into PNG format.
- hjkjj
