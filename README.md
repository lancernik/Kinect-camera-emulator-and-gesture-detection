# Kinect Camera Emulator




Step 1) Combine kinect and RGB to get best results in gesture detection \
Color-based detection is not accurate enought to be main hand-detection source,but will allow to increase gesture detection accuracy and complexity. Using deep-learning for hand detection will slow program too much, so it's better to use depth-sensor
![image](http://chemmaks.pl/Tutoriale/depth.png)
Hand sample: 
![image](http://chemmaks.pl/Tutoriale/hand_test.png)


Step 2) Train depth-detection algoritm to detect depth from RGB for specified room  (My room, with U-Net) \


Depth-detection-model:\
Input image: RGB camera image \
Mask output: Kinect depth map

Step 3) Home-made motion capture studio is ready
