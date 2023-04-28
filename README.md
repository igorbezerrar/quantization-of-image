
# Image quantization

This is a Python Jupyter Notebook that demonstrates image quantization. The notebook is written in Python 3 and uses the following libraries:

- NumPy
- pandas
- OpenCV
- matplotlib

## Description
The notebook loads an image and quantizes it using two different methods. The first method quantizes each pixel of the image by finding the closest value in a list of most frequent pixel values. The second method quantizes each pixel by taking into account the average of its neighbors.

## Usage
The notebook can be run in a Python environment that supports Jupyter Notebooks. It can be executed cell by cell, and the outputs will be displayed inline.

The input image is expected to be located at /content/images.jpeg.

The number of bits for quantization can be adjusted by changing the value of the variable BITS.

## Contents
The notebook contains the following code cells:

1. Loading the image and displaying its properties
2. Finding the most frequent pixel values in the image
3. Defining the first quantization method
4. Defining the second quantization method
5. Quantizing the image using both methods and displaying the results.


## Autores

- [@igorbezerrar](https://www.github.com/igorbezerrar)

