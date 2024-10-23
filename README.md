# Digital Image Project With Gui
This project focuses on applying various digital image processing techniques to a set of five different photos. To run the project, make sure you have the following libraries installed on your computer: numpy, tkinter, and cv2 (OpenCV).

## Installation

1. Install numpy library:
   pip install numpy
2. Install tkinter library:
   pip install tkinter
3. Install cv2 library:
   pip install opencv-python
   
## Project Overview

- The main program file is `Digital_Image_Processing_Project.ipynb`, located in the `Digital_image_processing` directory.
- The program allows you to apply one of the following filters to the photos: Average, Negative, Sharpen, Laplacian, or Logarithm.
- You will be prompted to enter a sensitivity value for comparison (e.g., 1, 2, 4, 16, 32, 64, 128, 255). This value represents the coefficient used to measure the amount of change between the filtered images and the original photos. It is recommended to choose values greater than 2 for more noticeable similarity changes.
- After applying the selected filter, the program calculates the similarity between the photos pixel by pixel. The similarity ratio is presented as a percentage for better understanding.
- For further details on the program's functionality, logic, and possible results, refer to the `Digital_Image_Presentation.pdf` file.

## Customization

If you decide to download and use the program on your computer, you will need to update the file paths of the photos accordingly. The directory named `1` contains the photos used for modifications.

Feel free to explore the project and experiment with different filters and sensitivity values!

## Contact
- For any inquiries or questions, please feel free to contact me at kadirqokdeniz@hotmail.com.
