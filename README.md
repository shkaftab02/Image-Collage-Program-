# Image-Collage-Program-
This program creates a collage by combining four images into a 2x2 grid. The images are resized to the dimensions of the smallest image in the set to ensure they fit neatly into the collage. The final collage is saved in the format specified by the user (JPG, PNG, or TIFF).
Features
•	Combines four images into a 2x2 grid.
•	Automatically resizes all images to match the size of the smallest image.
•	Saves the collage in JPG, PNG, or TIFF formats.
•	Handles errors such as missing or corrupted files. Requirements
•	Python 3.x
•	PIL (Python Imaging Library, part of the Pillow package) To install Pillow, run the following command:
Copy code
pip install Pillow How to Use
1.	Run the Program: Start the program by running the script.
2.	Provide Image Paths: The program will ask for the paths to four images. Ensure the paths are correct and point to valid image files.
3.	Output Format: You will be prompted to specify the format for the saved collage. Choose from jpg, png, or tiff.
4.	Collage Creation: The program will resize the images and create a 2x2 collage grid.
5.	Save the Collage: The collage will be saved with the name collage.<output_format> (e.g., collage.jpg).
Error Handling
•	File Not Found: If any of the provided paths do not exist, the program will raise a FileNotFoundError.
 
•	Corrupted Image: If any image is corrupted, an error will be raised, and the program will notify you.
•	Invalid Output Format: If an unsupported file format is entered, the program will display an error.
Example
If you provide the following images:
•	Image 1: image1.jpg
•	Image 2: image2.png
•	Image 3: image3.tiff
•	Image 4: image4.jpg
The program will create a collage in a 2x2 grid, resize them to the smallest image dimensions, and save the collage as collage.jpg (if you chose JPG as the format).
Code Explanation
1.	Input Parsing: The program asks the user for the paths of the four images.
2.	Image Loading: It verifies if the images exist and are not corrupted.
3.	Resizing: The images are resized to the dimensions of the smallest image.
4.	Collage Creation: The images are arranged in a 2x2 grid to form a collage.
5.	Saving the Collage: The collage is saved in the chosen file format. How to Run
1.	Save the script as Assignment3.py.
2.	Open your terminal or command prompt.
3.	Run the script with the following command:
4.	Copy code
5.	Assignment3.py
6.	Enter the image paths and output format when prompted.
