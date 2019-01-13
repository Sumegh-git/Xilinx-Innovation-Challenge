# Xilinx-Innovation-Challenge
# Team reverse_biased

# AUTOMATED-APPLIANCE SWITCHINGS
This is the code submission and video submission of our proposed project in `Xilinx Innovation Challenge` during Kshitij,2019 at IIT Kharagpur.

### Code Requirements:
1) OpenCV 2 or 3
2) Python 3.6
3)PYNQ-Z2 board(optional) - for hardware implementation

### Description:
This project uses OpenCV Python library to take in video-frames and process them , to detect the Hand-Gesture shown by the user
counting the number of fingers shown . Based on this , this can be implemented on Hardware to maybe `switch ON` T.V if the user shows 4 fingers
and `switch OFF` if user shows 4 fingers ; using `USB Webcam`
PYNQ-Z2 board is used for Accelerating the code for faster execution.

### Logic used for Image Processing:
Based on a fixed background we perform a background subtraction , blur the image and then find out the Binarised image of hand . Then
we perform Contour Detection and apply Convex Hull algorithm to determine the count of fingers.

### Procedure:

Execute `handgesture.py` and for the first 2 seconds keep the webcam faced towards a fixed background maybe a wall or something.
Once the working code has displayed `Background Captured!` then you can move on to bring your hand in front of the webcam , and the code will
process the image displaying the number of fingers shown.

### Contributors:
##### 1) [Sumegh Roychowdhury](https://github.com/Sumegh-git/)
##### 2) [Sombit Dey](https://github.com/sombitd)
