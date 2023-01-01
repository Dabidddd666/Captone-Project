# Capstone-Project
This is my capstone project. 
Description: in this project, you will be working on state prediction of a 4-fingered robot hand given RGBD (RGB + Depth) images. You are required to implement a simple supervised learning algorithm where you input RGBD images of the robotic hand from a top view, and output the positions (in meters) of the tip of each finger. You are required to submit your code to the Kaggle Compe- tition (http://www.kaggle.com/competitions/csci-ua-473-intro-to-machine-learning-fall-2022) and will be graded/ranked according to regression loss values of the output of your model. The evaluation metric for the competition will be the mean squared error (MSE) loss.
I add more experimental results and comments in readMe file and programming file. It is a detailed supports to my report.

Note that I keep my debugging process in the programming for further work, so it might be no smooth to read. I add comments to show the role of differnt cells

demo1: it is my inital attempt for the project. I shows my debug process, my demo CNN model shown in the reprot. The file is mainly for testing.

depth1: I mainly train depth image with my CNN Model2, batch_size = 64

depth2: I mainly train depth image with my CNN Model3, batch_size = 32

img0: I mainly train RGB image0 with my CNN Model1, batch_size = 32
comb_1: I mainly combine three RGB images and depth image together by channel concat with my CNN Model3 with batch_size = 8

comb_2: I mainly combine RGB image0 and depth image together by channel concat with my cnn Model3 with batch_size = 2


