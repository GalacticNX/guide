# Launching CFW

Now that the preparation work is out of the way, we're finally ready to launch custom firmware on the Switch.

Unlike systems such as the DSi, Wii, or 3DS, Switch CFW is currently volatile. It will only work as long as your Switch is on. As soon as your Switch completely loses power for any reason (shutting down, battery dying, etc.), CFW will no longer be active and you will need to follow these instructions again.

&nbsp;

!!! danger "Keep emuMMC offline at all times"
    Your emuMMC (emuNAND) should never connect to Nintendo. For online play, eShop browsing, or any other Nintendo online activity, use your sysNAND. Using both emuMMC and sysNAND online will likely result in a ban.

### Instructions

!!! tip ""
    1. Power on your Switch into RCM, and inject the Hekate payload
    2. Navigate to `Launch` using the touch screen
    3. Find `Atmosphere` and launch it

Your Switch is now booting into Atmosphere.

To verify Atmosphere launched properly, open the Settings applet, and navigate to System. You should see `AMS` next to the version number, as well as an `E` at the end, indicating you are booted into emuMMC.

&nbsp;

!!! tip ""
    ![Atmosphere version string](../img/launching-cfw-emummc-settings.jpg)

&nbsp;

### Launching the Homebrew Menu

You will now be able to launch the Homebrew Menu by opening the album or by holding the R button while launching any game (including demos/cartridges), or application (e.g. Youtube/Hulu). If R is not held, the game or application will launch like normal. Here is how to copy an app to emuMMC to use this feature:
	1. Copy the Nintendo folder on the root of your microSD card to the backup location on your computer.
	2. Reinsert the microSD card back into the console and boot normally (without hekate and RCM).
	3. Open the Nintendo eShop applet and download YouTube.
	4. Turn off the console and reinsert the microSD card back into your computer.
	5. Copy the Nintendo folder to the emuMMC/RAW1/Nintendo folder, selecting the merge or overwrite option when prompted.
	6. Delete the Nintendo folder from the root of the microSD card.
	7. Copy the other Nintendo folder (the backup you just made) back to the root of the microSD card.
	8. Reinsert the microSD card and boot into Galactic.
    
!!! warning "A note about using the album for the Homebrew Menu"
    - Using the album for the Homebrew Menu instead of a game or application has several limitations, including but not limited to: a smaller amount of available memory (RAM), as well as being unable to launch a full-featured web browser. It is strongly recommended to launch homebrew through applications or games instead. If your games don't show up as "installed" on your switch, copy the contents of the `Nintendo` folder from the root of the sd card to the `emummc/RAW1/Nintendo` folder
    
!!! tip "Adding new applications"
    - Place homebrew applications (`.nro` files) into the `switch` folder on your SD card, or download new homebrew right from the console via the "HB App Store" in `hbmenu`

&nbsp;

### What the included homebrew applications do

!!! tip ""
    - JKSV is a save manager, it can dump and restore saves from/to your system. For more information, see [Save Management](../../extras/save_management.md)

    - FTPD is a ftp tool for connecting your Switch's sd card wirelessly to your pc. Tools like WinSCP can connect to your switch on `(ip of switch):5000`

    - NX-Shell is a file explorer for the Switch. You can move files, listen to mp3's, view images etc.

    - NXThemeInstaller is a theme installer app. See the [Theming section of our guide](../../extras/theming.md) for more information

    - hbappstore is a homebrew app store where a large collection of switch homebrew is kept.
    
    - SysDVR lets you capture your Switch's screen and send it to your computer.
    
    - Goldleaf is a title manager. It lets you install things and browse the Internet.
   

&nbsp;

### Updating your setup

!!! tip ""
	Whenever a new Switch firmware update releases you may need to update your files to be able to use CFW on the new version. Make sure to follow the instructions on [this page](../../extras/updating.md) to update your setup correctly.
