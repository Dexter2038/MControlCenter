# MControlCenter

MControlCenter is a Free and Open Source GNU/Linux application that allows you to change the settings of MSI laptops.

## Features

 - CPU and GPU temperature display
 - Fan speed display
 - Change the maximum battery level limit
 - Change other settings such as keyboard backlight mode, USB Power Share, etc.

## Screenshots

![Info tab](/docs/img/screenshot_info.png?raw=true)
![Battery tab](/docs/img/screenshot_battery.png?raw=true)
![Settings tab](/docs/img/screenshot_settings.png?raw=true)

## Installation

The application requires the `ec_sys` module with option `write_support=1` to run.

This is QT application. You may need to install libqt5widgets5 to run.

### Installation from archive

1. Unpack the archive with the program
2. Open terminal in unpacked directory
3. Run the script `sudo ./install`
