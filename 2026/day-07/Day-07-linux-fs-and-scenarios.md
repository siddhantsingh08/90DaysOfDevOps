# Day 7 of 90dayschallenge

Part 1 Directory and Why they are required

- / - This is the starting point in the linux file system all other file folder branches out from the root directory forming a tree like structure 
- /home - this directory is use to store user data and the user create all the required file and folder in this directory
- /etc- this act as a nervous system of the linux file system all the config file are located here nearly all the app and service have there config file locates here 
- /var/log- this folder is the most important folder which is use to store variable data such as log,documents etc, this the most important folder for a devops engineer because all the logs for every service and app are stored here which help in debugging.
- /tmp- this folder is use to create file and folder which are short lived stores temprary file 
- /bin- this folder stores important command binaries which are required by the system to function in a single user mode 
- /sbin- this folder is similar to bin but it stores system binaries which is required by the admin user
- /lib - this folder contains shared lib that required by the binary of bin and sbin to function.


Part 2 Scenario based troubleshooting
-  Scenario 1 Service Not Starting

If a service like docker is not running on system 

First step i will check for the status of the service weather it is active or not 
using systemctl status docker
if it is in stopped state then i will start the service using systemctl start docker.io
if the serivce is active 
then i will check for log of that service 
in /var/log/docker
I will use tail -n 50 "Path" to check the logs and find out what is the main cause why the serivce is not running 

if even there we cannot find anything we can restart the service after checking for the dependency

- Scenario 2: High CPU Usage

If a issue aries due to high High cpu usage then i will ssh to that particular server 
first i will checl for the real time cpu usgae on that system using htop and top command to find out which of the process is using the max memeory 
Second then i will sort the process according to the usage then check for the maxmium process which is conusimg the cpu usage
Third I will check the process that is consuming the max cpu usage using ps -aux | grep "name" and check weather that process is a revelent process or it is zombie process that is consuimg the process
I will clear all the unnecessary process

- Scenario 3: Finding Service Logs

If i have to check for the logs of service 

First step i will check weather the service is up and running or not using systemctl command 
Then i will nevigate to /var/log/"" directory  to check the logs we can use tail -n 50 "path" or journalctl -u "name" - 50 to checkl for the logs pf that particular service 

- Scenario 4: File Permissions Issue

If i am not able to run a file 

then first i will neviagte to the file location using cd 
then i will check for the file permission using ls -la command 
if the permission is not given to execute the file then i will change the permission using chmod command and once done i will change the file permission back to normal
