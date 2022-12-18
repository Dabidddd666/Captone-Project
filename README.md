# Captone-Project
This is my capstone project. Please read the readMe file. 
I add more experimental results and comments in readMe file and programming file. It is a detailed supports to my report.

Note that I keep my debugging process in the programming for further work, so it might be no smooth to read. I add comments to show the role of differnt cells

demo1: it is my inital attempt for the project. I shows my debug process, my demo CNN model shown in the reprot. The file is mainly for testing.

depth1: I mainly train depth image with my CNN Model2, batch_size = 64, kaggle score: 0.04016

depth2: I mainly train depth image with my CNN Model3, batch_size = 32, kaggle score: 0.03005

img0: I mainly train RGB image0 with my CNN Model1, batch_size = 32, kaggle score: 0.04753

comb_1: I mainly combine three RGB images and depth image together by channel concat with my CNN Model3 with batch_size = 8, kaggle score: 0.07563

comb_2: I mainly combine RGB image0 and depth image together by channel concat with my cnn Model3 with batch_size = 2， kaggle score: 0.06331


