In this color detection Python project, I am going to build an application through which you can automatically get the name of the color by clicking on them. So for this, we will have a data file that contains the color name and its values. Then I will calculate the distance from each color and find the shortest one.

 I will be using a dataset that contains RGB values with their corresponding names. The colors.csv file includes 865 color names along with their RGB and hex values.

Plan of action:-
Taking an image from the user-->Next, read the CSV file with pandas-->Set a mouse callback event on a window--> Create the draw_function-->Calculate distance to get color name-->Display image on the window-->Run Python File.

**python color-detection.py -i colorpic.jpg**

Formula to calculate minimum distance:
d = abs(Red – ithRedColor) + (Green – ithGreenColor) + (Blue – ithBlueColor)



