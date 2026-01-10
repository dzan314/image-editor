# image-editor

## Overview

Custom ImageProcessor class for handling RGB (.png) and colormap (.pkl) files. It implements basic computer vision methods to alter images, relying on array operations. This project is part of coursework (assignment) of the Data Science & Artificial Intelligence BSc at Leiden University. 

## Features

- load: loads an image based after provding the filepath
- save: saves the (altered) image
- pixelate: pixelates a given area by taking mean of nearest (defined by the second argument) pixels
- blur: blurs the whole image
- rotate RGB colors: changes color of every pixel by rotating RGB values to the left (r, g, b -> g, b, r)
- a few helper methods for more complex methods

## Usage

Download the ``` image_class ``` file, and import it as a module, as in the file ``` example_use ```.
Follow standard Python file-handling guidelines.

#TODO: extend the features (and descriptions)
