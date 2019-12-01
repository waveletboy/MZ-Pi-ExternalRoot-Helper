MZ-Pi-ExternalRoot-helper
===============================

The original script is from [Adafruit-Pi-ExternalRoot-Helper](https://github.com/adafruit/Adafruit-Pi-ExternalRoot-Helper) which is not updatd since July 2015.

Using mz-pi-externalroot-helper
-------------------------------------

On a Raspberry Pi running Raspbian, with a USB-connected storage device you
wish to use for your root filesystem:

    git clone https://github.com/waveletboy/MZ-Pi-ExternalRoot-Helper.git
    cd MZ-Pi-ExternalRoot-Helper
    sudo ./mz-pi-externalroot-helper -d /dev/sda

...where `/dev/sda` is the external USB you wish to use for a root filesystem.

