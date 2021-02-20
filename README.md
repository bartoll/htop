htop for Raspberry Pi 4b
-------------------------------

**htop** Ubuntu deb packages modified to display CPU Frequency and CPU Temperature.

[![htop](https://github.com/bartoll/htop/blob/main/img/htop-screen1.png)]

# arm64

* Ubuntu 20.04

# Installing:

	sudo dpkg -i ./htop-3.0.5-temp1_arm64.deb
  
# Uninstalling:

 If you want to restore the stock package for any reason, type in shell:

	sudo apt-get remove --purge htop

 and then:

	sudo apt-get install htop

# Configuring

After install, please type F2 and add
 - CPU temperature (F2 -> Display Options -> Also show CPU temperature)
 - CPU frequency (F2 -> Display Options -> Also show CPU frequency)
