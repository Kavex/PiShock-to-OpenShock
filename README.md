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
7. Go to https://openshock.app on your PC and make an account
8. Grab your phone and connect to the SSID with OpenShock (OpenShock-XX:XX:XX:XX:XX:XX)
9. Once connected open the browser on the phone and go to 10.10.10.10 or openshock.local
10. Find your router's Wi-Fi network in the web-interface. (Does not support 5Ghz)
    
![image](https://github.com/user-attachments/assets/a5ff6680-a542-46df-bd1d-703a3727af03)
    
12. Log into https://openshock.app on your PC and go to Hub and click on the green circle with a white plus
13. It's going to make a New Hub, Go to the three dots and click on pair. It will give you a code.
14. Put that code in the web-interface on the phone and it will link your account.
15. Go to the Shockers on https://openshock.app on your PC and click on the green circle with a white plus
16. It's going to make a new shocker and you will want to pick the hub you just made and rename the shocker to something simple
17. Pick the model CaiXianlin and hit create
18. Turn on the shocker by clicking the power button once. You should hear one beep.
19. Now hold the shocker's power button until it blinking fast. `
20. While it's blinding fast click on the speaker icon under your shockers on https://openshock.app
21. Shocker should now be paired with OpenShock

## ShockOSC App
1. Download and install the latest [ShockOSC](https://github.com/OpenShock/ShockOSC/releases/)
2. Sign in with your OpenShock Account
3. You can follow this guide https://wiki.openshock.org/guides/shockosc-basic/
4. Make a group with named whatever you want (I used **GroupName**) and make sure to check your shocker that is linked
   
![image](https://github.com/user-attachments/assets/eb6d845a-7705-4966-a19b-bf8a1a948820)

![image](https://github.com/user-attachments/assets/fd0d839d-a177-4cab-b4d1-78998a21b845)

6. Set your configurion
   
![image](https://github.com/user-attachments/assets/fba68fd1-73b6-4049-a2c6-2a0ed139a119)

7. Move onto setting your VRChat Avatar


## VRChat Setup

1. Go to [Kyobinoyo's Openshock VRChat Prefab](https://github.com/Kyobinoyo/OpenshockPrefabs)
2. Download **Shocker, Remote Trigger, Settings Menu** and import them into Unity
3. Go to **Openshock\ShockOsc\Shocker\VRChat** and Add the **ShockOsc_VRChat_Shocker.prefab** to your avatar. Move it to the Left leg or wherever.
4. Unpack the prefab and go to **ShockOsc_VRChat_Shocker** > **Shocker** > **VRC Contact Reciever** and change it to your group name (I used **GroupName**).
   
![image](https://github.com/user-attachments/assets/ab2284db-5d17-404e-8a6f-1a636cec1fd6)

![image](https://github.com/user-attachments/assets/7c3ebe70-5824-461d-b1c2-7e4118a24fb8)

6. You may want to add other **Collision Tags** and add **Allow Self** like i have
7. Go to **Openshock\ShockOsc\Settings Menu** and add **ShockOsc_Settings.prefab** to your avatar
8. Go to **Openshock\ShockOsc\Remote Trigger** and add **ShockOSC_Receiver.prefab** and **ShockOSC_Sender.prefab**
9. Unpack and go to **ShockOSC_Receiver** > **Receiver** and change Custom to **OpenShock** and Parameter to your group name (I used **GroupName**). If you want to have it shock yourself then select **Allow Self**.
    
![image](https://github.com/user-attachments/assets/01410a29-822b-4429-aee0-1bb43142c089)

![image](https://github.com/user-attachments/assets/e29d53a1-4db8-4538-944a-8b3fee003185)

10. Unpack and go **ShockOSC_Sender** > **Sender** and set Custom to **OpenShock**
    
![image](https://github.com/user-attachments/assets/0af95772-6a0c-415a-951b-2661bc132f29)

![image](https://github.com/user-attachments/assets/90fd3155-7f24-4aa6-9cf1-69112d4951ec)



 



