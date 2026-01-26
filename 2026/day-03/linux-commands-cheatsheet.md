# Day 3 of 90dayschallenge
**Linux CheetSheet**
**1-Basic Commands used in daily life** 
- cd: This command is use to change the directory or nevigate to a particular location.
- pwd: this command is use to check the current working directory
- ls: this comamnd is use to list everything in a directory.
- ls -la : this command is use to list everything is details.
- mkdir: this command is use to create a directory.
- touch: this command is use to create a file
- cat: this command is use to read a file.
- head: this command is use to read the top 10 lines of file is there are 20 lines in files
- tail: this command is use to read the bottom 10 lines of line if there are 20 lines in files
- Uname (-r or -a): this command is use to check the Kernel Version.
- whoami: this command is use to check the hosname of the current user
- ip: this command is user to check the ip
- hostname: this command is use check hostname of the system.

**2-Networking commands**
- ping: this command is use tp check the internet connection or we can say if a website is up or not 
- traceroute: this command is use locate the ip between the source and destination
- nslookup: this command is check the ip address and if the website is working or not 
- netstat:
- mtr: this command is combition of ping and traceroute command

**3-File Management Commands** 
- Chmod: this command is use to change the permission of a file or folder 
- cp : this command is copy data of one file or folder to another file and folder (for coping folder we will use -r flag )
- mv: this command is use to rename a file or folder
- ln: this command is use to create a hardlink and softlink (Shortcuts) for softlink we will use(-s) flag along with ln.
- chown: this command is use to change the ownership of file and folder.
- umask: this command is use to check the by default permission of file or folder.

**4-Process Mangaement Commands**
- ps: this command is use check all the running process
- top: this command is to check all the process
- htop: this command is to check all the process and its real time usage.
- df -h: this command is to check the disk usage.
- nophup: this command ios use to run process in background.

**5-User Management Commands**
- Useradd: this command is use to create a new (Note this command require root permission so we need to run it with sudo)(Eg: Sudo useradd -m NewUser)
- passwd: this command is use create a password for the User(Eg: sudo passwd "NameofUser")
- userdel: this command is use to delete a user(Eg: Sudo userdel "NameofUser")
- Groupadd: this command is to create a group(Eg: Sudo groupadd Docker)
- gpasswd: this command is to add a user to a group(Eg: Sudo gpasswd "NameofUser" "Group")
- su: this commmand is use to switch to different user.
