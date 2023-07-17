# 相关命令

|              常用命令               |                       作用                       |
| :---------------------------------: | :----------------------------------------------: |
|              fdisk -l               |        查看所有磁盘分区,也可以查看物理盘         |
|              swapon -s              |                 查看所有交换分区                 |
|                df -h                |             查看磁盘使⽤情况及挂载点             |
|               df -hl                |                       同上                       |
|             du -sh /dir             | 查看指定某个⽬录的⼤⼩，没有/dir则默认为当前目录 |
|        du -sk * \| sort -rn         |          从⾼到低依次显示⽂件和⽬录⼤⼩          |
|      mount /dev/hda2 /mnt/hda2      |                    挂载hda2盘                    |
| mount -t ntfs /dev/sdc1 /mnt/usbhd1 |          指定⽂件系统类型挂载（如ntfs）          |
|  mount -o loop xxx.iso /mnt/cdrom   |                  挂 载 iso ⽂件                  |
|         umount -v /dev/sda1         |                  通过设备名卸载                  |
|        umount -v /mnt/mymnt         |                  通过挂载点卸载                  |
|         fuser -km /mnt/hda1         |                  强制卸载(慎⽤)                  |

