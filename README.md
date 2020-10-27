# A lane deperature warning algorithm based on https://github.com/JunshengFu/driving-lane-departure-warning

1. In order to detect the lanes, a HSV filter is used instead of a saturation filter to find the yellow lane and white lane seprately.
2. Canny edge detection is used to detect the edge of the lanes.

![Canny edge detection result:]
(https://github.com/tian-cthit/Lane-Detection/blob/master/examples/canny%20edge%20detection.png)

![Yellow lane detection result:]
(https://github.com/tian-cthit/Lane-Detection/blob/master/examples/yellow%20lane.png)

![Test case final result:]
(https://github.com/tian-cthit/Lane-Detection/blob/master/examples/canny%20and%20hsv%20result.png)
