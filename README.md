 RASPBERRY PI SETUP

 
![20200904_161449](https://user-images.githubusercontent.com/64540298/92244199-46187080-eecb-11ea-87e0-3cfe396f3e1c.jpg)


If you have a raspberry pi model  on your hand,you will learn how to setup NOOBS, Raspberry Pi Os, Raspberry Pi OS Lite, NOOBS Lite.  

**WHAT WE NEED IS THE HARDWARE AND PROGRAMS**

1.	RASPBERRY PI
2.	POWER CABLE
3.	POWER ADAPTER
4.	HDMI CABLE
5.	ETHERNET CABLE
6.	USB KEYBOARD AND MOUSE
7.	WIN 32 DISK IMAGER/ETCHER  (https://sourceforge.net/projects/win32diskimager/)  (https://www.balena.io/etcher/)
8.	SD CARD FORMATTER (https://www.sdcard.org/downloads/formatter/)
9.	SD CARD READER
10.	SD CARD 
You have to choose appropriate class 10 SD card your Raspberry Pi model.If you have an old Raspberry Pi model on your hand, you should choose 16-32 GB SD card. Because after installing, working slowly.

**SETUP**

NOTE: Raspberry Pi Os, Raspberry Pi Os Lite like operating system can print directly  on SD card. Or you can setup on NOOBS.

Raspberry Pi Os and Raspberry Pi Os Lite (Desktop support not available) operating system for install;

1.	Plug into the laptop your SD car reader and find appropriate SD card port our SD card type.

2.	Open SD Card Formatter programming and choose correct SD card. Make sure format correct SD card.


![4](https://user-images.githubusercontent.com/64540298/92241812-84139580-eec7-11ea-9af1-7c13256d7ea3.PNG)


3.	You connect https://www.raspberrypi.org/downloads/raspberry-pi-os/ . Choose appropriate operating system for your raspberry pi. You  can download via Zip or Torrent. If you prefer to download via Torrent, make sure have a Torrent programming.

 
![6](https://user-images.githubusercontent.com/64540298/92241734-66dec700-eec7-11ea-8e61-9580db89a506.PNG)


4.	You click right key and choose “Extract All”Now you see “Disk Image File”.


 ![7](https://user-images.githubusercontent.com/64540298/92241762-7231f280-eec7-11ea-9c67-b21ee1c96e14.PNG)



5.	Open Win32 Disk Imager and select disk imager file. Make sure select correct device.


 ![1](https://user-images.githubusercontent.com/64540298/92241902-a73e4500-eec7-11ea-89e4-85f3c7d2b97f.PNG)


6.	When finish printf, find sd card and click right key. So you can exit safely.

7.	Put in position your SD card into Raspberry Pi.

8.	After connecting USB keyboard, USB Mouse,power cable,HDMI cable, Ethernet cable you can give power Raspberry Pi.


**### After opening this screen, if turns off. You should do these.**


![rasp_0103 png](https://user-images.githubusercontent.com/64540298/92242072-ed93a400-eec7-11ea-9f77-1dc3f0093a74.jpg)


*Turn off power your Raspberry Pi and you remove SD card from the Raspberry Pi.

* Plug into the laptop your SD card reader and find appropriate SD card  port your SD card type.

*Open config.txt file.

*You need to disable the comment lines so you remove # symbol in front of the data.

*Have to change some values;

**hdmi_mode=4
hdmi_group=2
hdmi_force_hotplug=1
disable_overscan=0
overscan_right=24
overscan_left=24
overscan_top=24	
overscan_bottom=24
config_hdmi_boost=4
hdmi_ignore_edid=0xa5000080(If you don’t find this data in config.txt, add anywhere.)**


![ct](https://user-images.githubusercontent.com/64540298/92242281-3ba8a780-eec8-11ea-9f1d-6f5be4e6b4c4.PNG)
![ct2](https://user-images.githubusercontent.com/64540298/92242291-3e0b0180-eec8-11ea-98e6-381467f79ca6.PNG)
![ct3](https://user-images.githubusercontent.com/64540298/92242301-406d5b80-eec8-11ea-92aa-58e002d27b5b.PNG)





READY TO USE
