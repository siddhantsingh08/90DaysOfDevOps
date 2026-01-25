# day 2 of 90dayschallenge 

The core components of Linux:

Linux is an open-source operating system that is fast, secure, and reliable.
Linux was developed in 1991 by Linus Torvalds.
Linux is ideal for web hosting, networking, and automation.
Linux follows the General Public License (GPL).
Linux is CLI-based.
Linux is preferred in DevOps for automation, networking, and containerization. 


Linux has a three-tier architecture and works on the principle of ASK.
- The innermost layer is **Hardware**
- Then followed by the **Kernel**
- Then the **Shell**
- Last but not the least, **Applications**

**Kernel (Heart of Linux)**
The Kernel is the core of the Linux-based operating system.
It virtualizes the common hardware resources of the system to provide each process its own virtual resources.
It is also responsible for preventing and mitigating conflicts between different processes.

In layman term: The kernel is the main component that ensures everything in the system is functioning properly and smoothly.
Since a computer understands only binary language (**0s and 1s**), the kernel converts user requests into binary so the system can understand and perform tasks.

**Shell**
The Shell is the user interface of the Linux operating system that allows users to interact with the kernel using shell commands.
The shell interprets and executes these commands and acts as a bridge between the user and the kernel.

in laymen term : If you go to a shop to buy something, you tell the shopkeeper what you want.
Similarly, the shell acts like a shopkeeper—we tell it what we want, and it communicates with the kernel to get the work done.

**Appliaction**:
Applications are the medium through which users perform specific tasks on the system.


**Process**
Whenever we run a command in Linux, it starts a process.
**Everything starts with a process**.
Example:
If you create a folder (directory) in Linux, that action also runs as a process.
there are different kind of process 
- Foreground proccess 
- Background process

**Foreground Process**
Foreground processes are those that require the terminal.
They take input from the user and provide output.
While they are running, the terminal remains occupied.

eg : **pwd**
output: **/home/usr/**

**Background process**

Background processes run in the background and do not occupy the terminal.
We can run any process in the background using the & symbol at the end of the command.
 eg : pwd &

 there are many more process link 
 Zombie process
 Orphan process.

 **SystemD**
This is the first process that starts when we start the computer and remains active until we shut down our computer.

**PID (Process ID**) is the number given to each process, and once the process is complete or ends, the PID can be used by another process. However, two processes cannot have the same PID at once; it is unique.

**PID** for SystemD is **1**
 
