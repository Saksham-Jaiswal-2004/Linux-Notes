## Chapter 6: File Management in Linux

1. ls -l - to see file permissions

Folder Descriptors - Ex. drwxrwxr-x
d - directory
1st rwx - Your User Permissions - r -> Read, w -> Write, x -> Execute
2nd rwx - Group Permissions - r -> Read, w -> Write, x -> Execute
r-x - Other User Permissions - r-> Read, - No Write, x -> Execute

0 -> 000 -> ---
1 -> 001 -> --x
2 -> 010 -> -w-
3 -> 011 -> -wx
4 -> 100 -> r--
5 -> 101 -> r-x
6 -> 110 -> rw-
7 -> 111 -> rwx

chmod -  To change permissions, go inside a directory then run this to change its permissions, ex. chmod 777 -> rwxrwxrwx

File Descriptors - Ex. -rw-rw-r--
'-' - File
1st rw- - Your User Permissions - r -> Read, w -> Write, x -> No Execute
2nd rw- - Group Permissions - r -> Read, w -> Write, x -> No Execute
r-- - Other User Permissions - r-> Read, - No Write, x -> No Execute 

To change file permissions:
chmod 700 {filename} - all permissions to current user, no permission to group and other users

2. umask - By default permissions for new files, usually it is 0002 in AWS EC2 Linux -> All, All, Read-Execute -> 775

3. chown - To change ownership, ex. sudo chown {username} {filename}

4. chgrp - To change grouop, ex. sudo chgrp {groupname} {filename}

5.  zip - to compress files and folders, 
   ex. zip {destination} {content to zip}
   ex. zip -r {destination} {folder to zip}

6. unzip - to decompress zipped content, ex. unzip {filename}

7. gunzip - same as zip just zipped content extenstion will be different

8. tar - utility to compress files, 
   
   ex. tar -cvzf {destination}.tar.gz {source}
   tar flags
   c - compress
   v - verbos - to display
   z - to use gunzip
   f - to specify file
   
   ex. tar -xvz {compressed file}.tar.zp
   tar flags
   x - extract