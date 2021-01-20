# LEGO-SPIKE-PRIME-LIBRARY-FOR-PYTHON-MAC-Linux

Hello, You have seen to find my Python Liabrary for Lego Spike Prime coding, Lego Does Not Endorse This Page. 
This is a Open Source Library for spike prime python coding.
Before we Get Coding and installing specific things we need to know what the Lego Spike Pime Hub is made out of.
The hub is a micro python computer, This means Python Coding is simple and easy and we will not have to install python.
To Begin Coding We Need To Connect our Hub and make sure it is turned on. Connect the hub Via USB to Terminal to do this enter the following command.

ls /dev/tty.usbmodem*
        
After that, copy the 2nd to last line of code you see and then type     Screen    Followed by the SPACE key then paste the code we previously copied.            Making sure our hub is not connected press the enter key and you should see a lot of mumbo jumbo code appear (if not in full screen).

If you get a terminal error saying "Could Not Find A PTY" Make sure the Spike Prime App is not running and or reboot terminal and the hub.

I will soon make a upcoming youtube channel where it will show how you can code you own robots made for Spike Prime. 

This section will show you how to connect our hub via bluetooth (IF YOUR COMPUTER CAN SUPPORT IT).

Download VS CODE :https://code.visualstudio.com/download  Then install it
Make sure bluetooth is on and make a new .py file in vs code.
Open the terminal section and enter this

ls /dev/tty* | grep Hub

Then turn on the hub and copy the sencond to last line of code then type: screen        followed by the space key, and paste what we have previously copied then press ENTER and your hub should automatatically connect.


The Latest Liabrary.zip is present as a release and contains .PY files witch is sample code meant for the models in the spike prime app.
We need to verify the code of the hub to do this type   import hub         then type  


from spike import App


Initialize the app
app = App()

