license-plate-recognizer
========================

Script is written in Wolfram Mathematica. 
It takes all photos from "test" directory, searches area of license plate and saves result to "result" directory.

Performs next steps for each image:

 1. **Canny edge detection algorithm** 
 2. **Hough Transform** for line selection
 3. search for rectangle with specified ratio among all rectangles formed with  horizontal and vertical lines
 
###Example of work:###


![Alt text](https://raw.githubusercontent.com/s0ph1e/license-plate-recognizer/master/result/1.JPG)
![Alt text](https://raw.githubusercontent.com/s0ph1e/license-plate-recognizer/master/result/4.JPG)
![Alt text](https://raw.githubusercontent.com/s0ph1e/license-plate-recognizer/master/result/10.JPG)
![Alt text](https://raw.githubusercontent.com/s0ph1e/license-plate-recognizer/master/result/13.JPG)
