## Chapter 5: Users & Groups Management

#### System Level Commands
1. uname - Which platform is in use
2. uptime - Since when the system is running and number of users
3. date - current date and time
4. who - gives the current users login time and IP Address
5. whoami - just gives the current users username
6. which - Tells which resource we are using about the one we enquire for, ex. which bash, which java etc.
7. id - give the id and group id of the user you are logged in with
8. sudo - Superuser do, does a task with admin access or as a root user.
9. shutdown - Turn off
10. reboot - Restart
11. apt - Application Package Manager, used to manage and install applications
12. apt-get - Application Package Manager, used to manage and install applications from internet
13. yum - Same as apt but for CentOS
14. dnf - Same as apt but for Fedora
15. pacman - Same as apt but for Arch Linux
16. portage - Same as apt but for Gentoo Linux and Chrome OS
17. rpm - Same as apt but for RedHat

#### User and Group Management Commands
1. useradd - To add users, ex. sudo useradd -m {username}
2. passwd - to change password, ex. sudo passwd {username}
3. su - switch user, ex. su {username}
4. exit - to change user to primary user
5. userdel - to delete user, ex. sudo userdel {username}
6.  groupadd - to make a user group, ex. sudo groupadd {groupname}
7. gpasswd -a - to add users in groups, ex. sudo gpasswd -a {username} {groupname}
8. gpasswd -M - to add multiple users in groups, ex. sudo gpasswd -a {username},{username},{username} {groupname}
9. groupdel - to delete any group, ex. sudo groupdel {groupname}