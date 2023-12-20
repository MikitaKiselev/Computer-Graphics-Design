# Image Processing Application Readme

## Introduction
This Python application showcases various image processing techniques using the OpenCV and Pillow libraries. The graphical user interface (GUI) is implemented with Tkinter. The application enables users to apply different image processing filters and operations to an input image, visualizing the results in real-time.

## Requirements
Make sure to install the following libraries before running the application:
- OpenCV (`cv2`)
- Pillow (`PIL`)
- Tkinter

1. **Global Thresholding:**
   - Applies global thresholding with Otsu's method to create a binary image.

2. **Adaptive Thresholding:**
   - Applies adaptive thresholding using a Gaussian mean to create a binary image.

3. **Negative Image:**
   - Converts the image to its negative.

4. **Multiply by Constant:**
   - Multiplies each pixel value by a constant factor.

5. **Power of 2:**
   - Raises each pixel value to the power of 2.

6. **Linear Contrast Adjustment:**
   - Adjusts the contrast of the image using a linear transformation.

7. **Original Image:**
   - Displays the original input image.

## GUI Layout

- The GUI is divided into sections, each corresponding to a specific image processing technique.
- Each section includes a labeled original image and its processed version.

## Notes
- The application uses a fixed window size of 1400x700 pixels, but you can modify it as needed.

Feel free to explore the code and experiment with different images and parameters. If you encounter any issues or have suggestions for improvement, please open an issue on the GitHub repository.