# kernel-module-cheatsheet


sudo apt-get install build-essential kmod
sudo lsmod
sudo cat /proc/modules

what kernel header files are available?
apt-cache search linux-headers-`uname -r`
sudo insmod <module_name>.ko
sudo rmmod  <module_name>.ko
sudo journalctl --since "1 hour ago" | grep kernel