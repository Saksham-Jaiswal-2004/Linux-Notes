## Chapter 10: Linux Volume Management

1. lsblk - List all blocks
2. df -h - to get free volume

Mounting - To bind your volume to a location
Attaching - To attach your volume with your instace

![[Pasted image 20260521004604.png]]

3. lvm - logic volume manager
4. lvm -> pvcreate /dev/xvdf /dev/xvdg /dev/xvdh - making three volumes, physical volumes
5. pvs - to see all physical volumes
6. vgcreate - to create volume group
   ex. vgcreate {groupname} {physical volume name 1}, {physical volume name 2}, etc.
   physical volume name example - /dev/xvdf
7. pvdisplay - displays all information about physical volumes
8.  vgdisplay - displays all information about volume group
9. lvdisplay - displays all information about logical volumes
10. mkfs.ext4 - to format logical volumes
    ex. mkfs.ext4 {location}
11. mkfs -t ext4 - to format disk volumes
    ex. mkfs -t ext4 {location}
12. mount - to mount volumes,
    ex. mount {volume location} {location to mount volume}
13. lvextend - to extend logical volume 
    ex. lvextend -L +{Amount}G {jisko extend krna hai - logical volume path}

-> sudo su - Makes your current user root user