# Seam Carving with Enhanced Energy Mapping Using Semantic Segmentation

## Description
This project implements a seam carving algorithm for image resizing with enhanced energy mapping capabilities, utilizing semantic segmentation for improved context awareness. Seam carving allows content-aware resizing by removing seams (paths of low energy) from an image, preserving important visual features.

## Features
- Compute energy maps using Sobel filters.
- Enhanced energy mapping using semantic segmentation for better seam selection.
- Seam removal to resize images.
- Supports batch seam carving for multiple seam removals.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/lanlokun/seam_carving-.git
   cd seam_carving
   ```
2. Install dependencies: (optional)
   ```bash
   pip install -r requirements.txt 
   ```

## Usage
Run the project using the provided Jupyter Notebook:
1. Launch the notebook:
   ```bash
   jupyter notebook
   ```

2. In the seam_carving folder, Open the `Seamcarving++.ipynb` file in your browser.
3. Follow the step-by-step instructions in the notebook to load your image, configure the number of seams to remove, and visualize the results.

Replace `path/to/your/image.jpg` with the path to your image file when prompted in the notebook.

## Acknowledgments
- Inspired by the Seam Carving paper by Avidan and Shamir.
- Uses OpenCV and NumPy for image processing.
- Guided by our instructor, Professor Wang Jing.

