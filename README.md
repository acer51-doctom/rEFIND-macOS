# rEFIND-macOS
How to install rEFIND on macOS.

1st step:
Download the latest release.

2nd step:
Unzip it and copy to an usb stick or you can manually create a partition, with atleast 2GB, and paste to there.
IMPORTANT: You need to remember the name you selected to the usb stick or partition. I will use "REFLASH".

3rd step:
Boot the system to recovery mode.
On Intel: Command+R
On ARM: Hold the power button until you see the options menu appear.

4th step:
Select your user and enter the password. 
Once you are in macOS Utilities, press ⇧+⌘+T; you will land in the Terminal.

ALTERNATIVE: In the menu bar, go to Utilities>Terminal.

5th step:
Type this one at a time:

```
cd /
ls
cd Volumes
ls
cd REFLASH
ls
cd refind-bin-0.14.0
ls
./refind-install
```

6th step:
Reboot and you should see rEFInd.

