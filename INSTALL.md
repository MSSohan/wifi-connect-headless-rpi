# Installing wifi-connect-headless-rpi

## NOTE: This application only installs and runs on Linux.

### Log into the Raspberry Pi from an ssh connection. The command below assumes the raspberry pi name is headlesswifi. Use the name you used during the SD card imaging.
`ssh pi@uprint.local`

### Update the system
`sudo apt-get update`

### Install Git. The default Raspberry Pi OS does not have git installed.
`sudo apt-get install git`

### Clone this repo
1. `git clone https://github.com/MSSohan/wifi-connect-headless-rpi.git`
1. `cd wifi-connect-headless-rpi/scripts`

### Install both Network Manager if you need and then wifi-connect
`sudo ./rpi_headless_wifi_install.sh` 

### Running
Rebooting the rpi will automatically run the `./run.sh` script\
 `sudo reboot` 

With a direct connection to the rpi, you can manually run the `./run.sh` script.\
More info is also found at by reading the [RUN.md](RUN.md) file.

