# fedberry-config
A utility for making common Raspberry Pi configuration changes via a simple menu-driven interface. The majority of the configuration changes result in automated modifications to `/boot/config.txt` and/or other standard Fedora configuration files. Many options will require a reboot to take effect.

## Main Features:
* Enable / Disable Device Tree overlays
* Enable / Disable Device Tree parameters
* Enable / Disable hardware support / drivers including:
  * Mesa VC4 driver(s)
  * RPi Camera driver
  * Linux Infrared Remote Control (LIRC) support
  * Realtime Cock (RTC) support
  * Bluetooth support for RPi3
* Expand (grow) root filesystem on SD card
* Select which kernel you want to use at boot 
* Add and enable swap files
* Set SELinux modes (enforcing, permissive, disabled)
* Show current system information

---

![screenshot](https://cloud.githubusercontent.com/assets/16171842/19257047/0ffa8e1e-8f9f-11e6-9cc8-cd3c1a84b03c.png)
