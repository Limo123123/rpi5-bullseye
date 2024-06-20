# Raspberry Pi 5 Bullseye
This is an Image for the Rpi 5 with the Old Bullseye System. But the image is Pi4 Compatible

# What Works?
- Mesa Drivers - Yes, But not Properly - Vc4,.... Disabled in Config.txt
- Terminal - Yes - With no Chromium Opened
- File Manager - Yes -
- Pi Desktop Button - Yes - ~Could be~ Mesa Driver 24.x.x
- Chromium-Browser - Yes - With Mesa Driver 24.x.x
- Other Desktop Icons, z.b. Wlan, Bluetooh - ~No~ Works, but no Window Icons - ~Could be~ From the Mesa Driver, Except four Volume

# Mesa Drivers
The Problem is that the Mesa Drivers from Bullseye are too old.
You can uncomment them in the Config.txt.
If you have any Ideas to fix that go to the Issues page. (Go to Closed)
Used Mesa Drivers: Mesa 24.x.x  Updated with PiKISS
