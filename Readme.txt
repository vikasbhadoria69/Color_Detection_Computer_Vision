# Colour Detection using Pandas & OpenCV
* Extracted color RGB values and the color name of a pixel from an Image.
* Created events like double-clicking on the window.
* Read CSV files with pandas and performed operations on data.

## Code and Resources Used
**Python Version:** 3.7  
**Packages:** pandas, numpy, OpenCV.

## About the Python Project
In this color detection Python project, application has been built through which one can automatically get the name of the color by clicking on them. A data file that contains the color name and its values has been used and then the shortest distance from each color has been calculated.

## What is Colour Detection?
Colour detection is the process of detecting the name of any color. For humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the color. Since childhood, we have mapped certain lights with their color names. In this project somewhat the same strategy to detect color names has been used.

## Dataset
Used a dataset that contains RGB values with their corresponding names. The colors.csv file includes 865 color names along with their RGB and hex values.
Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. In the dataset, we need to map each color’s values with their corresponding names. In this project a dataset that contains RGB values with their corresponding names has been used. The CSV file for the dataset has been taken from this [link](https://github.com/codebrainz/color-names/blob/master/output/colors.csv)

## Methodology
* Taking an image from the user
* Read the CSV file with pandas
* Set a mouse callback event on a window
* Create the draw function
* Calculate distance to get color name
* Display image on the window
* Run Python File.

### Formula to calculate minimum distance:
**d = abs(Red – ithRedColor) + (Green – ithGreenColor) + (Blue – ithBlueColor)**

### Command for programm to run
**python color-detection.py -i colorpic.jpg**

