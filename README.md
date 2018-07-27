# raspiCamMatlab
Face Detection using Raspberry pi camera and matlab

Step 1: In matlab go to Add-Ons > Get hardware support pakages. It will open Ass-On Explorer.

Download: matlab support packages for Raspberry pi hardware

step 2: Now connect raspberry pi with host computer and check the connection into command window using following command

  rpi = raspi('192.168.2.75','pi','Viral1043'); #To connect raspberry pi to matlab through Enthernate cable

  cam = cameraboard(rpi, 'Resolution', '640x480'); #To open camera connected with raspberry pi
  
step 3: Clone or Download repositories and run the 

