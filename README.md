# rtl8188eus_drivers
wifi adapter drivers TL-WN722N
 RTL8188EUS
802.11bgn USB 2.0 Network Interface Controller 

* sudo apt update
* sudo apt install bc
* sudo rmmod r8188eu.ko
* git clone https://github.com/aircrack-ng/rtl8188eus
* cd rtl8188eus
* sudo -i
* echo "blacklist r8188eu" > "/etc/modprobe.d/realtek.conf"
* exit
* make
* sudo make install
* sudo modprobe 8188eu
