# WiFry.img Version 0.1 Beta
this is a simple project. We have used the Kali Light version for the Rasberry 2/3 right from kali.org. We have installed the kali-linux-wireless package. And Wifijammer made by DanMcInerney (https://github.com/DanMcInerney/wifijammer), the system currently uses xfce for the window manager, it is set to auto login and auto start the wifijammer script. 

Next we plan on using a more light weight Linux distro
Requirements:

1) 16Gig MicroSD is pretty much required with this version because well kali is a big of for a Ras to handle. 
2) External Wifi card that supports packet injection and all that funness!. 
3) POWER, don't work without power, we have tested with a PNY external power pack with a 1 amp usb powered out. We were able to successfully jam Wifi for about a 15-20 foot range. Of course we got much better performence when plugged into a normal power outlet. 

TODO:

- We need to make the img smaller so this can be used with smaller MicroSD cards
- we need to make the operating system more light weight to save on the resources. 
- Test the platform on multiple different Rasberry Pi Builds. 
- Maybe try and add in a touchscreen display for a bit more fun. 
