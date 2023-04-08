# Fly-LCD 43/50/70

The diplay can be purchased from here https://www.aliexpress.com/item/1005005257187800.html

for DSI setup, you will need to add following setting into config.txt
Please be aware for the direction when you insert the FFC cable.

sudo nano /boot/config.txt

add following 2 lines
dtoverlay=vc4-kms-v3d
dtoverlay=vc4-kms-dsi-7inch

![image](https://user-images.githubusercontent.com/41975091/230713794-68b2c551-52fa-439a-a7c1-d003cfeb8f0b.png)

Then save and sudo reboot now.
