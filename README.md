### Tracking-a-balls-trajectory-from-video-using-OpenCV-and-LS
Tracking a ball's trajectory from a video and plotting the curve using Standard Least Squares method for a noisy and a non noisy video

### How to run the code
### Step 1
Just copy and paste all the files in a folder (including the videos)

### Step 2
For running all the codes you need to create an environment first and then install the libraries. 
Install required packages onto your virtual environment. Replace “myenv”with your environment name.
Enter the following commands in your terminal window. Press ‘y’ when prompted. 
a. conda create -n myenv python=3.7
b. conda activate myenv
c. conda install -c conda-forge opencv=4.1.0
d. conda install -c anaconda numpy
e. conda install -c conda-forge matplotlib
f. conda install -c conda-forge imutils
g. (optional) conda install spyder=4.2.0
h. (optional) spyder
i. pip3 install sympy 

### Step 3
After installing all the libraries, we are ready to run the codes. All the codes are in jupyter notebook format
q2 is for problem 2, which requires the video file. Keep the files in the same location as where the code files and your environment is (or else change the path in the below line in the codes accordingly) cap = cv2.VideoCapture('file_path/ball_video2.mp4').
Just press shifter enter to run each cell individually or elese run all the cells from the editor menu. Or else type 'python3 file_name.py' by going to the file location in the terminal.

### Note
q_3 is for problem 3, after installing the libraries, it can be run directly in any editor (preferrably VSC) or google colab also. The graphs will show you the different plots.
q4 is the code for problem 4, where I have written the code to compute SVD from scratch. Tt can be run directly in any editor (preferrably VSC) or google colab also.
