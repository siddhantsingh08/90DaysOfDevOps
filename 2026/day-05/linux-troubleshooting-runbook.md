# Day 5 of 90dayschallenge 

I have used nginx(docker container) as the target service and will be debugging it on various conditions:

- **Uname -a** 
This command i have used to check the kernel version 

<img width="1714" height="192" alt="image" src="https://github.com/user-attachments/assets/b243a159-ad3a-4290-b8c4-e68c8ee387a5" />

- **Systemctl Status Docker**
This command is used to check weather docker is installed or not and is active or not 

<img width="1703" height="562" alt="image" src="https://github.com/user-attachments/assets/f8c6dce1-a98a-4ba8-9bf3-193ff423e0d5" />

- **docker ps**
this command I have used to check the running containers 

<img width="1695" height="509" alt="image" src="https://github.com/user-attachments/assets/c068793f-b4b6-4488-89b6-9725dff61d4f" />

- **htop**
this command i have used to check the real time usage of CPU "Nginx"

when container was running
<img width="1696" height="859" alt="image" src="https://github.com/user-attachments/assets/f927f440-216f-4966-a529-28e36556ca3d" />

when container was stopped
<img width="1684" height="617" alt="image" src="https://github.com/user-attachments/assets/1f2295ae-631d-46f6-b806-322f4dfea03b" />

- **du -sh "path"**
this command i have used to check the disk usage 

when container was running
<img width="1716" height="200" alt="image" src="https://github.com/user-attachments/assets/2de649e7-5fe3-4b31-8bd2-40fae53ff1db" />

when container was stopped 
<img width="1721" height="84" alt="image" src="https://github.com/user-attachments/assets/6e7c77d8-e9f9-46eb-a765-fb990656aac8" />

- **curl - "http://localhost:8080/"**
this command i have used to test the connection 

<img width="1617" height="600" alt="image" src="https://github.com/user-attachments/assets/ba5c88b2-0069-46db-b97f-2e2aa0bbd488" />

when connection lost 
<img width="1532" height="101" alt="image" src="https://github.com/user-attachments/assets/84aa3f7d-4e82-4215-8d65-f086012eb98f" />


- **tail -n "path"** 
This command i have used to check the logs i have stopped and started the service to see variation in logs 

logs when container was running 
<img width="1702" height="810" alt="image" src="https://github.com/user-attachments/assets/9623fab2-0b45-44de-a5f9-fe91c6f7e040" />

logs when container was stopped 
<img width="1702" height="792" alt="image" src="https://github.com/user-attachments/assets/dfe123c0-3727-45e8-b0f3-2d227e555c69" />

logs of docker 
<img width="1704" height="529" alt="image" src="https://github.com/user-attachments/assets/e998a2d8-41c5-4ac6-8045-9ed705ddefcf" />

