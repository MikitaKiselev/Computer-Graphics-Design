# Image Information Extractor
This is a Python script that allows you to select a folder containing images and extracts information about these images, such as image name, size, resolution, color depth, and compression. It also provides an option to save this information to a CSV file and display it in a graphical user interface using Tkinter.

# Prerequisites
Python 3.x
The following Python libraries:
os
pandas
tkinter (usually included in Python standard library)
PIL (Python Imaging Library, commonly known as Pillow)
# Usage
Run the script.
Click the "Select Image Folder" button to choose a folder containing images.
The script will recursively search for image files (with extensions .jpg, .jpeg, .png, .gif, .bmp) in the selected folder and its subdirectories.
Information about the images will be displayed in a table in a new window using Tkinter.
You can save this information to a CSV file by clicking the "Save as CSV" button.
The script will prompt you to choose the save location and filename for the CSV file.
# Customization
You can customize the script as needed. For example, you can modify the file extensions for image recognition, the appearance of the Tkinter table, or any other aspect of the script to better suit your requirements.

# Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or feature enhancements, please feel free to open an issue or create a pull request.
