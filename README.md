# Image_Colorization
Term Project for Machine Learning Course

Purpose of this project is colorizing gray scale images.

Generally, classical colorization methods can be broadly separated into three categories:	
1.  scribble-based colorization  (generally optimization based)
2.	example-based colorization  (generally optimization based and/or machine learning based)
3.	learning-based colorization  (generally machine learning based)

In this project, we implemented 'example-based colorization' only using Machine Learning.

For example, we have a source image;

![p027, a_source](https://user-images.githubusercontent.com/44112288/107850205-c1366900-6e11-11eb-8c89-806dba7d1e09.png)

Our program creates the gray scale version of source image and tries to learn how to detect each pixel values from gray-scale to source image by the help of feature vectors.
After that, the model takes a target image to colorize, and makes predictions.

Target Image:

![p027, b_target](https://user-images.githubusercontent.com/44112288/107850299-7537f400-6e12-11eb-957e-4bfe59cf6164.png)

Colorized version of target image:

![tree_2](https://user-images.githubusercontent.com/44112288/107850379-ea0b2e00-6e12-11eb-8e60-7dda8c93a216.png)


Libraries;  
numpy, 
pandas, 
matplotlib, 
scipy, 
opencv-contrib v.4.5.1

opencv-contrib:in case you don't have it, run pip uninstall opencv then run pip install opencv-contrib-python

You also need to change "path" variable in the code to path of the dataset 
