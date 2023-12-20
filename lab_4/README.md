# Rasterization Algorithms Application Readme

## Introduction
This Python application provides an interactive interface for visualizing various rasterization algorithms using Tkinter. The implemented algorithms include step-by-step drawing, DDA (Digital Differential Analyzer), Bresenham's line algorithm, Bresenham's circle algorithm, Castle-Pitway algorithm, and Wu's algorithm for anti-aliased line drawing.

## Requirements
Make sure to have the following libraries installed before running the application:
- Tkinter

## How to Run the Application
1. Clone the repository or download the source code files.
2. Open a terminal and navigate to the project directory.
3. Run the application using the following command:
   ```bash
   python filename.py

# Usage
1. Upon running the application, a Tkinter window will appear with input fields for coordinates and buttons for each algorithm.
2. Enter the starting and ending coordinates for the desired shape or line.
3. Click on the corresponding algorithm button to visualize the rasterization process.

# Implemented Algorithms
1. **Step-by-Step Algorithm:**
   - Provides a step-by-step visualization of the line drawing process.

2. **DDA (Digital Differential Analyzer) Algorithm:**
   - Draws a line using the DDA algorithm.

3. **Bresenham's Line Algorithm:**
   - Draws a line using Bresenham's line algorithm.

4. **Bresenham's Circle Algorithm:**
   - Draws a circle using Bresenham's circle algorithm.

5. **Castle-Pitway Algorithm:**
   - Draws a line using the Castle-Pitway algorithm.

6. **Wu's Anti-aliased Algorithm:**
   - Draws an anti-aliased line using Wu's algorithm.

# GUI Layout
- The GUI is divided into two sections: input menu and canvas display.
- Input menu includes entry fields for coordinates, scale, and time, as well as buttons for different algorithms.
- The canvas display shows the drawn shapes with grid lines.

# Notes
- The application supports visualization of rasterization algorithms in a 2D space.
- Adjust the scale parameter to control the granularity of the grid.
- The time window displays the execution time of the chosen algorithm.

