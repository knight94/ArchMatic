# Arch Linux Post Installation Setup and Config Scripts

This README contains the steps I do to install and configure a fully-functional Arch Linux installation containing a desktop environment, all the support packages (network etc.), along with all my preferred applications and utilities. The shell scripts in this repo allow the entire process to be automated.

### System Description
I prefer to run XFCE desktop because it's fast, clean, and lightweight. I've tried nearly every other Linux desktop and a few window managers, but I keep coming back to XFCE.

Slim login Manager is used and systemd for loading the modules.

---

The install steps are as follows:

### Install Arch Linux

Format the micro sdcard using the scripts in __[Pi Arch Linux Installation](https://github.com/knight94/arch-pi)__

### Boot into new installation
And Login as root

    $  [pi-login]: root (Default password is root) 

---

### Run ArchMatic files
Run the following scripts:

    $   ./0-pacman.sh
    $   ./1-xorg.sh
    $   ./2-xfce.sh 
    $   ./3-chrome.sh 
    $   ./9-setup.sh

### Reboot

    $   reboot

Congrats!

You should now have an Arch system running XFCE, with all the base packages that allow network connectivity and a curated selection of applications.
