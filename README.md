# **Udacity Self-Driving Car Nanodegree - Finding Lane Lines on the Road** 


##Overview

This is the first project of Udacity Self-Driving Car Nanodegree. This project is to identify lane lines on the road in images and videos.

> When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.
> 
> In this project you will detect lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  
> 
> To complete the project, two files will be submitted: a file containing project code and a file containing a brief write up explaining your solution. We have included template files to be used both for the [code](https://github.com/udacity/CarND-LaneLines-P1/blob/master/P1.ipynb) and the [writeup](https://github.com/udacity/CarND-LaneLines-P1/blob/master/writeup_template.md).The code file is called P1.ipynb and the writeup template is writeup_template.md 
> 
> To meet specifications in the project, take a look at the requirements in the [project rubric](https://review.udacity.com/#!/rubrics/322/view)


This repo contains the code, brief write up and output images and videos.

**Output Image**

<img src="test_images_output/solidWhiteCurve.jpg" width="480" alt="Driving Lane Image" />

**Output Video**

<video width="480" height="270" controls>
  <source src="test_videos_output/solidWhiteRight.mp4" type="video/mp4">
</video>

##Prerequisites

* Python 3.6
* Numpy
* OpenCV
* Matplotlib
* Jupyter
* Pillow
* Scipy
* ffmpeg
* Moviepy

##Files
* P1.ipynb - The main code
* Writeup.md - The brief explanation of the pipeline.
* Main Outputs
  * [test_images_output](test_images_output) 
  * [test_videos_output](test_videos_output)
* Step outputs
  * [test_images_output_gray](test_images_output_gray)
  * [test_images_output_cannyedge](test_images_output_cannyedge)
  * [test_images_output_houghline](test_images_output_houghline)
  * [test_images_output_maskededge](test_images_output_maskededge)
  * [test_images_output_houghlineseg](test_images_output_houghlineseg) 
 
##Setting Up

from Udacity
>
> ##Installation
> 
> ###If you have already installed the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) you should be good to go!   If not, you should install the starter kit to get started on this project. ##
> 
> **Step 1:** Set up the [CarND Term1 Starter Kit](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/83ec35ee-1e02-48a5-bdb7-d244bd47c2dc/lessons/8c82408b-a217-4d09-b81d-1bda4c6380ef/concepts/4f1870e0-3849-43e4-b670-12e6f2d4b7a7) if you haven't already.
> 
> **Step 2:** Open the code in a Jupyter Notebook
> 
> You will complete the project code in a Jupyter notebook.  If you are unfamiliar with Jupyter Notebooks, check out <A HREF="https://www.packtpub.com/books/content/basics-jupyter-notebook-and-python" target="_blank">Cyrille Rossant's Basics of Jupyter Notebook and Python</A> to get started.

> Jupyter is an Ipython notebook where you can run blocks of code and see results interactively.  All the code for this project is contained in a Jupyter notebook. To start Jupyter in your browser, use terminal to navigate to your project directory and then run the following command at the terminal prompt (be sure you've activated your Python 3 carnd-term1 environment as described in the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) installation instructions!):
> 
>`> jupyter notebook`
>
> A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook.  Follow the instructions in the notebook to complete the project.  
> 
> **Step 3:** Complete the project and submit both the Ipython notebook and the project writeup
> 
> ## How to write a README
> A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).

