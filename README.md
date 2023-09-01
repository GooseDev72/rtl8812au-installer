# rtl8812au (8812au) installation scripts
Install rtl8812au driver on your Linux desktop.
## Supported distros
### Debian/Debian-based distros
Working!
### Ubuntu/Official flavours/Ubuntu-based distros
Working!
### RPM (Red Hat)-based distros 
In Development!
### Fedora/Fedora-based distros
Almost working! (Fedora 38 is not working because of invalid kernel)
### Arch Linux/Arch-based distros 
Working!
### Manjaro Linux/Manjaro-based distros
Working!
### openSUSE/openSUSE-based distos
Working!
### Void Linux/Void Linux-based distros
Working!
### Alpine/Alpine-based distros 
In Development!
### Script work
It updates package base.
It installs needed packages.
It clones driver files from Github. (all distros use different drivers, see FAQ.)
It makes driver base (only for Morrownr's driver).
It builds and installs driver using DKMS.
It automatically reboots.
## FAQ
### Which driver it uses?
### Debian/Debian-based distros  
Will use aircarck-ng's driver
### Ubuntu/Official flavours/Ubuntu-based distros 
Will use aircarck-ng's driver
### RPM (Red Hat)-based distros 
Will use Gnab's driver
### Arch Linux/Arch-based distros including Manjaro 
Will use Gnab's driver
### openSUSE/openSUSE-based distos 
Will use Morrownr's driver
### Void Linux/Void Linux-based distros 
Will use Morrownr's driver
### Alpine/Alpine-based distros 
Will use Morrownr's driver
### No option for Manjaro?
It is an Arch Linux with GUI setup.
Use Arch script.
### No option for Ubuntu?
Use Debian installer.
Ubuntu is built on Debian.
### How do I run it?
In order to download rtl8812au git driver files, you need Internet.
Use Ethernet or USB modem in your Android phone.
Open your directory in terminal. 
Run sudo sh RTL8812AU-(distro).sh
Or sudo ./RTL8812UA-(distro).sh
### Any isssues?
It reboots automatically.
Write your issue in "Issues" tab.
### What I have to do?
Run it (see "How do I run it?")
It will do everything.

