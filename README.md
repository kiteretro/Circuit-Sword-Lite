# Circuit-Sword-Lite
Kite's Circuit Sword Lite

Welcome to the software repository for Kite's Circuit Sword Lite. This repo contains most/all of the software for the large all-in-one handheld gaming circuit boards, known as the Circuit Sword Lite.

_PRE-ORDER SIGN UP NOTIFICATION: https://goo.gl/forms/e97uUvPOfUxPWdz82_

![](https://i.imgur.com/ibdWkuw.png) Follow me on Instagram: http://instagram.com/kiteretro

![](https://i.imgur.com/s4VyfJG.png) Like my work? Why not buy me a coffee: http://ko-fi.com/kiteretro

# Where do I start?
Start by reading the wiki! It contains everything from the software setup to the hardware guides, and also troubleshooting!

https://github.com/kiteretro/Circuit-Sword-Lite/wiki

# Installing the software
Pick ONE of the following:

## Downloading the pre-made images
The easiest way to start is to download the pre-built image from the 'releases' tab:

https://github.com/kiteretro/Circuit-Sword-Lite/releases

1. Download the appropriate image for your board, and then unzip and write the .img to an SD card (e.g. using win32diskimager)
2. That's it, power on and you are ready to go! No further steps required!

This image is provided to make it easier to debug and get the thing booted properly. The images were built using the scripts in the `build` directory. You can create your own images with the steps found inside.

## Installing on top of a fresh distribution image

1. Download a base image
2. Unzip and write the .img to an SD card (e.g. using win32diskimager)
3. Boot with HDMI out or so
4. Enable WIFI and SSH
5. `git clone https://github.com/kiteretro/Circuit-Sword-Lite`
6. `cd Circuit-Sword-Lite`
7. `sudo ./install.sh YES` 
8. `reboot`

## Building your own image
Follow the instructions in the 'build' directory.

# Updating your existing installation
## Updating Base Software
Once updated and rebooted, you will most likely also need to update the Circuit Sword software (see below) to re-apply any existing fixes that may have been undone by the update.

## Updating the Circuit Sword Lite software
The installation includes an update script! This will perform the necessary actions to pull latest changes and apply them to your running installation.

1. Enable WIFI and SSH
2. `cd Circuit-Sword-Lite`
3. `sudo ./update.sh YES`
