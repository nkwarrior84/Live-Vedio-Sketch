# Live-Vedio-Sketch about the project

I am going to make a Real-time/ live Sketch  making script using OpenCV in Python. OpenCV makes it very easy for us to work with  images and videos on the computer. We will also make use of Numpy and Matplotlib to make this live sketch app

# About the kernal
Kernels in computer vision are matrices, used to perform some kind of convolution in our data.
Convolutions are mathematical operations between two functions that create a third function. 
In image processing, it happens by going through each pixel to perform a calculation with the pixel and its neighbours.
The kernels will define the size of the convolution, the weights applied to it, and an anchor point usually positioned at the center.

# Sharpning the resize image
Applying the sharpening filter will sharpen the edges in the image. 
This filter is very useful when we want to enhance the edges in an image that's not crisp.

# Appling Bluring
In Gaussian Blur operation, the image is convolved with a Gaussian filter instead of the box filter.
The Gaussian filter is a low-pass filter that removes the high-frequency components are reduced.


VideoCapture() Function is used to capture video either from the camera or already recorded video. cap variable returns a boolean value (True if able to retrieve/capture video successfully, False if not able to successfully capture the video). It takes one parameter:

0 – Front Camera
1 – Rear Camera
If the Cap returns True, then read() function is applied to it and it returns two things:

Boolean Value (Was it successfully able to read the frame, If yes)
Returns the frame of the video.
Each Frame is sent to a sketch() function that takes frame as input parameter and manipulates it to return sketch of the frame.

Don’t forget to release the captured video at the end of the while loop. Otherwise, it will consume all your machine’s memory.
