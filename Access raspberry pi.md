# Acessing the raspberry pi.
### Here one of the most common method of remote access to the raspberry pi will be descride (On Windows).
* Once you have installed the OS into the memory card. insert the memory card into the raspberry pi.
* [Download](http://www.putty.org/) Putty which is a simple software to access your pi over ethernet.
* Give the power supply to the raspberry pi through usb cable from your PC, you will see that pi's power led will glow and system led will start blinking. Wait for about 5 second let the pi to be intianlized.
* Connect the raspberry pi to the PC through Ethernet cable. you will see that pi's ethernet port will start bliking.
* connect your laptop to wi-fi or mobile hotspot. you can keep your mobile data off if you are connecting your mobile hotspot because we only need hotspot not data.
* now goto internet and sharing section in control pannel of windows.in change adapter setting right click in the connected wi-fi. goto properties. select the sharing tab. and allow the internet sharing over "ethernet".
![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/change-adapter-settings1.gif)
![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/wireless-modem-properties.gif)
![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/wireless-terminal-properties.gif)
* now goto cmd and run command ipconfig 
![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/2017-11-02%20(2).png)
* in my case ip address of pi was 192.168.1.8. it couldn be diffrent for you some like 192.168.137.1..2..3.. etc.
* you can also check ip address py pinging the pi using command "ping raspberrypi.mshome.net".
* after that open the putty enter the address which you got.

![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/putty.JPG)

* make sure ssh is selected in putty. Then click on open.


![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/FBU2BDUH7NLY7OG.MEDIUM.jpg)


* Once the terminal opens write the "pi" in front of "login as" and hit enter.
* then enter the password which is by default "raspberry".

![alt tag](https://github.com/dheera123/Set_Up_The_Raspberry_pi/blob/master/images/ssh-win-window.png)

* If you get the output as shown above then hurray..... :) you are inside the terminal of raspberry pi.
* You can do almost every thing that you can do in any other linux terminal.

