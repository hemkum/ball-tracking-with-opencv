# ball-tracking-with-opencv
code to track a ball using opencv and plotting graph of position vs time.

required : python3 along with these libraries: numpy, matplotlib, pandas, opencv.
for opencv installation in GNU/Linux, use this https://docs.opencv.org/2.4/doc/tutorials/introduction/linux_install/linux_install.html

code cas be run as : python ball.py
this will use camera of laptop for video.

or, python ball.py --video file.mp4
a video file as argument can be parsed using above format.

this will generate a .csv file and a .svg plot.
video can be interrupt by pressing q or closing the video window.
