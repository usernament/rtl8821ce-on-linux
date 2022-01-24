# rtl8821ce-on-linux
A guide for installing the drivers that RTL8821CE needs to work properly.
## Before the Linux distro installation
* Download rtl8821ce-master.zip
* Copy it into a USB.
## After the Linux distro installation
* If the installation manager tell you to reboot, reboot.
* Copy the rtl8821ce-master.zip in the folder you want.
* Open the terminal in the folder where rtl8821ce-master.zip is.
* Extract the file. If you have `unzip`, you can use `unzip rtl8821ce-master.zip` to extract rtl8821ce-master.zip in the same folder it is.
* Finally insert the next code lines:\
`cd rtl8821ce-master` for getting in the rtl8821ce-master folder,\
`chmod +x dkms-install.sh` for changing the permissions of dkms-install.sh,\
`chmod +x dkms-remove.sh` for changing the permissions of dkms-remove.sh, and\
`sudo ./dkms-install.sh` for installing the drivers.
