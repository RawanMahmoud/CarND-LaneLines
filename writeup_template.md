# **Finding Lane Lines on the Road** 


---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report


[//]: # (Image References)

[image1]: ./test_images_output/download.png "output"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I used canny function then hough function then add weight to draw the lines  

In order to draw a single line on the left and right lanes, I modified the draw_lines() function by calculating each slope of the lines and getting average the slope of the left and right side.

If you'd like to include images to show how the pipeline works, here is how to include an image: 

![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when the colour of the line is not clear due to the shades of trees.




### 3. Suggest possible improvements to your pipeline

A possible improvement would be to apply a color transformation and to fix it with the shadows of the trees.
