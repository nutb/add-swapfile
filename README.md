# add-swapfile
Create and mount SWAPFILE and add value "vm.swappiness=5".

Requirements
------------
Ubuntu or Centos system and some free space on the disk.

Distros tested
------------
Currently, this is only tested on ubuntu 14.04 and centos 6.7. It should theoretically work on older versions of Ubuntu or Debian based systems.

Usage
------------
oneinstack_memory
```shell
wget https://raw.githubusercontent.com/nutb/add-swapfile/master/memory.sh && chmod +x memory.sh && ./memory.sh
```
msergiy87/add-swapfile
```shell
wget https://raw.githubusercontent.com/nutb/add-swapfile/master/swap_add.sh && chmod +x swap_add.sh && ./swap_add.sh /swapfile 1G
```
Remove
```shell
wget https://raw.githubusercontent.com/nutb/add-swapfile/master/swap_remove.sh && chmod +x swap_remove.sh && ./swap_remove.sh
```
