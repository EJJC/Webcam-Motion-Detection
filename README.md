# Webcam-Motion-Detection
The is a python script to track motion in the webcam/camera of the user and record the times when motion Occured. 

The Program will connect to the users Webcam and initialise with a picture take from the webcam view. The next frames will be
compared to this initial frame and any change in the frame will be tagged on screen. This works best when the webcam is still and 
the initial frame is a background photo of the area. 

The program used basic image processing techniques to perform the delta analysis in each successive frame. 

The times of motion will the be recorded and output in a CSV file once the user presses the 'q' key to quit the program.

This program was done as part of my python upskilling.
