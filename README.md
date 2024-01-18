# MATLAB Assignment 1 - Filter/Effect

### Author: Kevin Horta

## Required

MATLAB R2023b

Librarys: Image Processing Toolbox Library for MATLAB

## Sample Screenshot

![image](https://github.com/vzkevin/Mountain-Processing/assets/100811318/a1b67734-3f08-4410-a695-ac90953e3447)


## Introduction

This MATLAB script is designed to apply a grayscale filter to an image and then perform erosion and dilation using image processing methods within a MATLAB live script.

## Reading Image

The script begins by reading an image into MATLAB using the `imread()` function. The desired image is selected using the `uigetfile()` function, and its filename is assigned to the variable `Filename`.

![image](https://github.com/vzkevin/Mountain-Processing/assets/100811318/006140b8-f612-4d69-a2dc-cfbf343f8e16)


## Displaying Image

The loaded image is then displayed using the `imshow()` function.


## Applying Filter

A grayscale filter is applied to the image using the `im2gray()` function, converting the RGB pixel values to a single brightness value.


## Applying Effect

A structuring element in the form of a 4x4 square is created, and it is used for opening the image, which involves erosion and dilation. The result is then displayed using 

## Saving PNG Image

The script provides the user with a choice to save the processed image as either PNG or JPG. The `listdlg` function is used to prompt the user for their selection, and the image is saved accordingly with a filename "NEWIMAGE1".

![image](https://github.com/vzkevin/Mountain-Processing/assets/100811318/50a53eb6-f39a-49e2-9b6b-da1d1bbc4a6e)

