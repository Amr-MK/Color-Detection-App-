Image Color Picker
This is a simple Python application built using tkinter and Pillow that allows you to open an image, display it in a window, and then click on any pixel to get its RGB and Hexadecimal color values. It's a handy tool for designers, developers, or anyone who needs to quickly identify colors within an image.

Features
Open Image: Easily load image files (PNG, JPG, JPEG, GIF, BMP) from your local system.

Interactive Color Picking: Click anywhere on the displayed image to instantly retrieve the color information of that specific pixel.

RGB & Hex Display: Shows both the RGB (Red, Green, Blue) tuple and the hexadecimal color code (e.g., #RRGGBB).

Pixel Coordinates: Displays the exact (x, y) coordinates of the clicked pixel on the original image.

Image Scaling: Automatically scales the image to fit the window while maintaining its aspect ratio.

Dynamic Resizing: Adapts the image display when the application window is resized.

Initial Image Load: Can be configured to load a default image upon startup.

Requirements
Before running the application, ensure you have Python installed (Python 3.6+ is recommended).
You will also need the Pillow library.

Installation
Install Python: If you don't have Python, download and install it from python.org.

Install Pillow: Open your terminal or command prompt and run the following command:

pip install Pillow

How to Use
Save the Code: Save the Python code (provided previously) into a file named, for example, color_picker.py.

Run the Application: Open your terminal or command prompt, navigate to the directory where you saved color_picker.py, and run:

python color_picker.py

Open an Image:

The application will attempt to load the default image specified in the code (C:\CS\VS Code\download.jpg).

If that image is not found or you wish to open a different one, click the "Open Image" button. A file dialog will appear, allowing you to browse and select an image file from your computer.

Pick a Color: Once an image is displayed on the canvas, simply click anywhere on the image.

View Color Info: The RGB and Hexadecimal color values, along with the pixel coordinates, will be displayed below the image.

Example (Conceptual)
Imagine you open an image and click on a bright red part. The application might display:

RGB: (255, 0, 0) | Hex: #FF0000
Coordinates: (150, 75)

If you click on a dark blue part:

RGB: (0, 0, 128) | Hex: #000080
Coordinates: (300, 200)
