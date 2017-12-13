# Asus_USB-53 Kernel-4.10.0-Drivers (Ubuntu_16.4 or Fedora or Arch or Any Linux)
  Asus AC1200 USB-AC53 Nano <br />
  8822BU for Linux <br />
  Driver for 802.11ac USB Adapter with <br />
  RTL8822BU chipset <br />
  
# Instruction: 
make clean <br />
make <br />
make install <br />
modprobe -v 88x2bu <br />
Output: insmod /lib/modules/4.13.16-302.fc27.x86_64/kernel/drivers/net/wireless/88x2bu.ko


# Testing:
Tested with Fedora or Ubuntu or Arch or any Linux with below kernel version <br />
Kernel: 4.10.0-xxx.xxxxx.x86_64 <br />
