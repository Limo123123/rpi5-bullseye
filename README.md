# Raspberry Pi 5 Bullseye
This is an Image for the Rpi 5 with the Old Bullseye System. But the image Should Pi4 Compatible

# What Works?
- Mesa Drivers - Yes, But not Properly - Vc4,.... Disabled in Config.txt
- Terminal - Yes - With no Chromium Opened
- File Manager - Yes -
- Pi Desktop Button - Yes - With Mesa Driver 24.x.x
- Chromium-Browser - Yes - With Mesa Driver 24.x.x
- Other Desktop Icons, z.b. Wlan, Bluetooh - Works, but no Window Icons - From the Mesa Driver, Except four Volume

# Mesa Drivers
The Problem is that the Mesa Drivers from Bullseye are too old.
You can uncomment them in the Config.txt.
If you have any Ideas to fix that go to the Issues page. (Go to Closed)
Used Mesa Drivers: Mesa 24.x.x  Updated with PiKISS

# How do I Build Myself Images?
To Build your own Images, you need a Pi 4 and z.b. A Sd card or something else where you can boot from.
Boot the Bullseye Image on your Pi 4. Run sudo apt update and sudo apt upgrade -y . 
Then you run sudo rpi-update to update the Kernel Version and its generating for the Boot needing files
Before you switch to the Pi 5 Make sure you deactivate the Drver Vc4 Driver Initalation. Just Comment it
We have to Upgrade the Mesa Driver. In this tutorial im using *PI-KISS* I wont use it anymore. You can build It Manual.
I would Recommend to Install Pi-Kiss before you switch to the pi 5.
If you Installed Pi Kiss, open the Terminal Window and open Pi kiss. You'll find an Option where stands Update Mesa Driver (Or simething else)
If its Installed reboot your i 5. Then Chromium should open and other thinks work then too.
If you want tu build it yourself, please refer to the guide from Mesa.

# Informations
Bullseye is not Officialy Supported on the Pi 5. Bullseye is now in Unstable. I Higly Recommend using Bookworm than Bullsseye.
My Questions are: Why do some of you hate Bookworm?, And Why is Ubuntu Server so hard to setup?, Why do some of you like Bullseye more?
You can Answer it in the Issue Tab if you like :) Before I forgot, I will Upload the Images on Source Forge because they are to big for Github.
To Help this Project you will to have to edit Images and will have to open a Pull Request where you Puplish a readme file where how to fix that Problem stands.
I wont recommend to use PiKiss anymore. I am supporting Pi-Apps, but if PiKiss's Repository Owner dosen't want to Contribute for the PiKiss version for Pi-Apps, i wont use it anymore.
I just wanted to say this. I don't mean that you mustn't use PiKiss. It's just an recomendation.
