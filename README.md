# **Finding Lane Lines on the Road** 


---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: result.jpg 

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

1.Converting the images to grayscale
2.Applying Gaussian smoothing Module
3.Using Canny Edge Detection Module
4.Selecting the region of interest
5.Applying Hough Tranform line detection
6.Combining images.

![alt text](https://i.imgur.com/ljy9OfN.png)

And I modeified the draw_lines() function to get the lines' slopes and connect it.

### 2. Identify potential shortcomings with your current pipeline

To do the image processing,maybe it has more faster and widely method to do. And when angle of the road is too curved, it will not detect the road.
 
### 3. Suggest possible improvements to your pipeline

Useing another way to find road or using the color to define the line.
