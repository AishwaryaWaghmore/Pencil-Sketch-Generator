# Pencil-Sketch-Generator

A Python-based application that converts images into realistic pencil sketches using OpenCV and Tkinter. This project is a simple yet powerful demonstration of image processing techniques, enabling users to transform their favorite photos into pencil sketch artworks with just a few clicks.

  	  

Features
	•	Image-to-Sketch Conversion: Converts images into detailed pencil sketches using advanced image processing techniques.
	•	Intuitive File Selection: Opens a file dialog to let users easily select their desired image.
	•	Cross-Platform Compatibility: Works seamlessly on Windows, macOS, and Linux.
	•	Lightweight and Fast: Processes images efficiently with minimal processing time.
	•	Support for Multiple Image Formats: Accepts .jpg, .jpeg, .png, and .bmp file formats.


  	  

How It Works
	1.	The user selects an image using a file dialog.
	2.	The script performs the following image processing steps:
		•	Converts the image to grayscale.
		•	Inverts the grayscale image.
		•	Applies Gaussian blur to the inverted image.
		•	Combines the original grayscale image with the inverted blurred image to create a pencil sketch effect.
	3.	The output pencil sketch is displayed and saved to the same directory as the input image.


  	  

Installation
Prerequisites
	•	Python 3.6 or later
	•	opencv-python library
	•	tkinter library (comes pre-installed with Python in most cases)

Steps
	1.	Clone this repository or download the script file.git clone https://github.com/your-username/pencil-sketch-converter.git
		cd pencil-sketch-converter
	2.	Install the required libraries:pip install opencv-python(Tkinter is included with Python, but if not, refer to your platform-specific installation guide.)
	3.	Run the script:python pencil_sketch_converter.py


  	  

Usage
	1.	Run the script:python pencil_sketch_converter.py
	2.	A file dialog will appear. Select the image you want to convert.
	3.	The script will process the image and:
		•	Display the original image and the pencil sketch.
		•	Save the pencil sketch in the same directory as the original image, appending _pencil_sketch to the filename.


  	  

Example
Input Image:

![alt text](https://github.com/AishwaryaWaghmore/Pencil-Sketch-Generator/blob/main/images/pin.jpeg?raw=true)

Output Pencil Sketch:
