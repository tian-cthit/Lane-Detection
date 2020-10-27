# Lane Departure Warning System for Autonomous Driving

This is A lane deperature warning algorithm based on https://github.com/JunshengFu/driving-lane-departure-warning, new methods are implemented to achieve lane detection and bugs caused by version upadte are fixed.


1. In order to detect the lanes, a HSV filter is used instead of a saturation filter to find the yellow lane and white lane seprately.
2. Canny edge detection is used to detect the edge of lanes instead of using a single Sobel filter. 
3. Dilation is used to enhance the edge detection result.


Canny edge detection result:
![Canny edge detection result](https://github.com/tian-cthit/Lane-Detection/blob/master/examples/canny%20edge%20detection.png)

Yellow lane detection result:
![Yellow lane detection result](https://github.com/tian-cthit/Lane-Detection/blob/master/examples/yellow%20lane.png)

Test case final result:
![Test case final result](https://github.com/tian-cthit/Lane-Detection/blob/master/examples/canny%20and%20hsv%20result.png)
