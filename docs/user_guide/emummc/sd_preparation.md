# SD Preparation

We will now place the required files for GalacticNX on the SD card.

Atmosphere has its own bootloader, called fusee. For the purposes of this guide we will be using Hekate+Atmosphere (hekatmosphere) instead, so that we can back up the system's NAND (internal storage) and take advantage of other advanced features in the future.

&nbsp;

!!! warning "File name extensions"
    If you use Windows, you should enable file name extensions before continuing. See [this link](../../extras/showing_file_extensions.md) for a guide on how to do this.

&nbsp;

### What you need

!!! tip ""
    - The latest release of <a href="https://github.com/GalacticNX/galactic/releases/latest/download/galactic.zip" target="_blank">Galactic</a> (Download the `galactic.zip` release of Galactic.

### Instructions

!!! tip ""
    1. Insert your Switch's SD card into your PC
    2. Copy *the contents of* the Galactic `.zip` file to the root of your SD card
    3. If you were already using your microSD card as a storage device for your games and backed up the Nintendo folder before partitioning your microSD card, please place it back on the root of your microSD card.
    4. Reinsert your SD card back into your Switch

    !!!danger "About emummc.txt"
        Putting the `emummc.txt` file provided by this guide into `/atmosphere/hosts` will prevent your emuMMC (emuNAND) from connecting to Nintendo. Not doing this will likely result in a ban.

    !!! tip ""
        Your SD card should look similar to this. The `Nintendo` folder will not be present if your switch has not already booted with the microSD card inserted.
        ![sdfilesimg](../img/sdfiles.png)

&nbsp;

#### [Continue to Making EmuMMC <i class="fa fa-arrow-circle-right fa-lg"></i>](making_emummc.md)
