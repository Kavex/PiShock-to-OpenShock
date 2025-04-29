# PiShock-to-OpenShock

This is for the PiShock Hub [2023 Model](https://wiki.openshock.org/hardware/boards/pishock/2023-pishock/) and the [PiShock CaiXianlin](https://wiki.openshock.org/hardware/shockers/caixianlin/#media)

## ESP32 Driver

1. Download drivers from here [CP210x Universal Windows Driver](https://download.openshock.org/drivers/CP210x_Universal_Windows_Driver.zip)
2. Extract the zip file
3. Run the CP210xVCPInstaller_x64.exe installer file then reboot your computer

## Flashing PiShock Hub 

1. Plug in the PiShock Hub into the computer with a USB C that works with Data 
2. Go to https://next.openshock.app/flashtool
3. Select the COM the PiShock Hub is on. Would look like COM14 or something
4. Select the PiShock 2023 Board
5. Check Erase before flashing and flash the device
6. Once done unplug the Hub and replug back in
7. Go to https://openshock.app/ on your PC and make an account
8. Grab your phone and connect to the SSID with OpenShock (OpenShock-XX:XX:XX:XX:XX:XX)
9. Once connected open the browser on the phone and go to 10.10.10.10 or openshock.local
10. Find your router's Wi-Fi network in the web-interface. (Does not support 5Ghz)
    
    ![image](https://github.com/user-attachments/assets/a5ff6680-a542-46df-bd1d-703a3727af03)
    
12. Log into https://openshock.app/ on your PC and go to Hub and click on the green circle with a white plus
13. It's going to make a New Hub, Go to the three dots and click on pair. It will give you a code.
14. Put that code in the web-interface on the phone and it will link your account.
15. Go to the Shockers on https://openshock.app/ on your PC and click on the green circle with a white plus
16. It's going to make a new shocker and you will want to pick the hub you just made and rename the shocker to something simple
17. Pick the model CaiXianlin and hit create
18. Turn on the shocker by clicking the power button once. You should hear one beep.
19. Now hold the shocker's power button until it blinking fast. `
20. While it's blinding fast click on the speaker icon under your shockers on https://openshock.app/
21. Shocker should now be paired with OpenShock

## ShockOSC App
1. Download and install the latest [ShockOSC](https://github.com/OpenShock/ShockOSC/releases/)
2. Sign in with your OpenShock Account
3. More coming soon

## VRChat Setup

Coming Soon!

https://wiki.openshock.org/guides/shockosc-avatar-setup-vrc/

https://kyobinoyo.gumroad.com/l/cqnsk

https://kyobinoyo.gumroad.com/l/idkbu

https://kyobinoyo.gumroad.com/l/xhxukh

