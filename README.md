# OrangePiOne-DietPi
An image of DietPi for the orange pi one SBC.



I created this image of the dietpi distro because I wanted support for allwinner H3 devices, in this particular case the Orange pi One.


Based on an armbian image and converted into a DietPi (Debian) system.

The whole system has been compressed into an image by using the dietpi-imager script and DD.
Some dependencies had to be added to make the conversion work, the armbian keychain had to be modified. Out of the box the Buster mainline was absolutely not suited for conversion into dietpi due to many keychain errors.
