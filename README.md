# geometric_parameters
A Python 3.0 package to derive narrowest neck width, hip-axis length and diameter of the femoral head from outline points placed by BoneFinder

This information is to guide the use of the attached script. 

*This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, 
either version 3 of the License, or (at your option) any later version. You should have received a copy of the GNU General Public License along with this software. 
If not, please see https://www.gnu.org/licenses/licenses.html*

1) Outline points are needed to use this script. BoneFinder is freely available software to do this automatically or manually (http://bone-finder.com). The model to place the points automatically is available there. 

2) The outline points need to provided in the format shown by example_pointsfile.txt. Each row after the "{" is an x,y coordinate for the points. 
The row after "{" will be read as point 0 by the code. The next row is point 1, the next row point 2 and so on and so forth until "}" ends the points file.  

3) These points files need to be stored in the same folder

4) A list of points files needs to be provided for the script - see example_list.txt

5) The code is written in Python 3 and best opened in Jupyter Notebook where each function is a cell

6) If you have a different number of points from the 85 described in this work then you will need to alter the circle fitting definitions.
 
7) To use this code on Right Hips then the circle interception code needs to be altered unless the images have been flipped to appear like Left sided hips.
 
 If you need any further advice please email ben.faber@bristol.ac.uk
