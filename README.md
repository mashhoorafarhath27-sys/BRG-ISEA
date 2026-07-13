# BRG-ISEA
## Introductionto server Environments and Architectures

**Student Name:** Mashhoora Farhath

## Overview

This repositoycontains all practical lab activities completed for the BRG-ISEA module. Throughout these labs, I gained practical experience in Linux administration, cloud computing, Bash scripting, Docker, DNS, SSL/TLS certificates, and server automation.

## Session 1a - Linux Setup
### Objectives

-Install Ubuntu using oracle VirtualBox.
-Create a GitHub repository.
-Learn basic Linux commands.
-Explore the Linux file system.

<img width="1920" height="1020" alt="Screenshot 2026-07-14 053257" src="https://github.com/user-attachments/assets/b15b4970-4ac4-4431-ac18-2c7a31e39d49" />


**Oracle VirtualBox showing the Ubuntu virtual machine.

<img width="1280" height="800" alt="Screenshot From 2026-07-14 05-34-34" src="https://github.com/user-attachments/assets/bb3d8d7f-e9bf-42d1-a6f5-41f056de8457" />

**Ubuntu desktop after successful installation.

<img width="652" height="490" alt="Screenshot From 2026-07-13 21-46-09" src="https://github.com/user-attachments/assets/fd756cee-935d-4cbb-9d70-810cc046fa17" />


**Basic Linux cammands ('pwd', 'ls', 'mkdir', 'cd','touch', 'nano', and 'cat') executed successfully to create directories, create and edit files, and display file contents.

### Commands Practised
-pwd
-ls
-cd
-mkdir
-touch
-nano
-cat

### Outcome

Successfully installed Ubuntu using oracle VirtualBox and became familiar with basic Linux commands for navigating directories and managing files.

## Session 1b-1 - Exploring Linux

### Linux Services

I used 'systemctl' command to view and manage Linux services. I checked the status of system services to understand how Linux controls background processes and verifies whether a service is active and running.

<img width="654" height="530" alt="Screenshot From 2026-07-14 06-05-27" src="https://github.com/user-attachments/assets/5333d4fa-b26d-458c-900a-212560352151" />

### 1b-2 - File Permissions and Ownership

I used the 'ls -l' command to view file permissions and the 'chmod' command to modify them. I changed the permissions of 'file1.txt' from '644' to '755' and then back to '644', verifying the chnages with 'ls -l'.

<img width="1280" height="800" alt="Screenshot From 2026-07-14 04-31-23" src="https://github.com/user-attachments/assets/2a8fd713-93bd-4cc5-8aaa-04cf7cfc2ef9" />

I used the 'chown' command to change the ownership of 'file1.txt' from one user to another. I verified the ownership change using 'ls -l' command to confirm that the file owner had updated successfully.

<img width="654" height="530" alt="Screenshot From 2026-07-14 06-01-05" src="https://github.com/user-attachments/assets/0c3406e3-c2d8-49cd-8c41-41afb01569f0" />

### 1b-3 - Searching Files 

I used the 'find' command to locate 'file1.txt' in different directories. I also used the 'grep' command to search for the word **Mashhoora** inside 'notes.txt'.

<img width="1280" height="800" alt="Screenshot From 2026-07-14 04-35-02" src="https://github.com/user-attachments/assets/323b35b2-5fe7-4191-898b-0557d5e22b27" />

### Outcome 

Successfully explored Linux service management, file permission, and file searching. I gained practical experience using 'systemctl', 'chmod', 'find', and 'grep' to manage and search files within the Linux environment.

## Session 2a - Total Cost of Ownership (TCO)

### Objectives

- Compared cloud infrastructure with on-premise infrastructure.
- Learned about hardware, software, maintenance, and licensing costa.
- Underdtood the financial benefite of cloud comuting.

### Description

During this session , I learned the concept of Total cost of Ownership (TCO) by comparing traditional on-premise infrastucture with cloud-based solutions. I explored how cloud computing reduces upfront hardware costs, minimizes maintenance, and provides scalability while allowing organizations to pay only for the resources they use.

## Outcome

This session improved my understanding of how cloud computing helps organizations reduce operational costs, improve flexibility, and simplify infrastucture management.

## Session 2b - Cloud Services

### Objectives

- Created an Amazon EC2 Ubuntu instance.
- Connected to the instance usingEC2 Instance connect.
- Updated the operating system.
- Installed software packages required for the lab.

### AWS EC2 Instance

I launched a free-tier Ubuntu EC2 instance using Amazon Web Services (AWS). After the instance was created successfully, I connected to it using EC2 Instance Connect.

SCreenshot

screenshot

### Updating the Sysytem

After connecting to the Ubuntu server, I updated the package repository using 'sudo apt update' and upgraded the installed packages using 'sudo apt upgrade -y'. This ensured the server was running the latest available software and security updates.

screenshots

### Outcome 

Successfully launched and managed a cloud-based Ubuntu server using Amazon EC2. I connected to the server remotely and updated the operating system, gaining practical experience with cloud infrastructure mamagement.
