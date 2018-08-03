# RaspiCamMatlab
Face Detection using Raspberry pi camera and matlab

## Step 1: In matlab go to Add-Ons > Get hardware support pakages. It will open Ass-On Explorer.

Download: matlab support packages for Raspberry pi hardware

## Step 2: Now connect raspberry pi with host computer and check the connection into command window using following command

You can check your raspberry pi IP using Advance IP scanner or by typing "$ifconfig" in raspberri pi terminal.

    rpi = raspi('<IP address>','<Username>','<Password>'); #To connect raspberry pi to matlab through Enthernate cable

    cam = cameraboard(rpi, 'Resolution', '640x480'); #To open camera connected with raspberry pi
  
## Step 3: Clone or Download repositories and Edit Ip address, Username and Password in RaspidetectFace.m 

## Step 4: Run the RaspidetectFace.m in matlab
