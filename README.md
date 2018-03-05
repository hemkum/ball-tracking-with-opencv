# ball-tracking-with-opencv
code to track a ball using opencv and plotting graph of its position vs time.

required : python3 along with these libraries: numpy, matplotlib, pandas, opencv.
For installation of opencv in GNU/Linux, use this https://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html

Command to run code:
`python ball_tracking.py`  
this will use camera of laptop for video capture.

You can also parse video file as argument:  
`python ball_tracking.py --video file.mp4`  

this will generate a .csv file and a .svg plot.
video can be interrupt by pressing q or closing the video window.
