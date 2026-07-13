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

<img width="1920" height="1020" alt="Screenshot 2026-07-14 071320" src="https://github.com/user-attachments/assets/ef464a97-4793-4535-b226-5078dd1dd60b" />


<img width="1920" height="1020" alt="Screenshot 2026-07-14 071346" src="https://github.com/user-attachments/assets/9cf96cb8-f815-4298-b1ff-b4b5351d36be" />


### Updating the Sysytem

After connecting to the Ubuntu server, I updated the package repository using 'sudo apt update' and upgraded the installed packages using 'sudo apt upgrade -y'. This ensured the server was running the latest available software and security updates.

<img width="1920" height="1020" alt="Screenshot 2026-07-14 071417" src="https://github.com/user-attachments/assets/04b059c5-2ca9-4d9f-a1dd-1a30fd4d26d0" />


<img width="1920" height="1020" alt="Screenshot 2026-07-14 071433" src="https://github.com/user-attachments/assets/4d716e40-fcd7-4e51-bb8f-9c783747f780" />

### Outcome 

Successfully launched and managed a cloud-based Ubuntu server using Amazon EC2. I connected to the server remotely and updated the operating system, gaining practical experience with cloud infrastructure mamagement.

## Bash Scripting

### Objectives

- Created a Bash script.
- Added executable permissions using 'chmod +x'.
- Executed the script successfully.

### Script Created

'''bash
#!/bin/bash
echo "Hello, Mashhoora!"
echo "Welcome to Bash Scripting."
date
'''

<img width="651" height="526" alt="Screenshot From 2026-07-14 00-55-29" src="https://github.com/user-attachments/assets/c7768cc0-2b1d-4f82-ab50-c1fe6be96e54" />

<img width="651" height="526" alt="Screenshot From 2026-07-14 00-54-51" src="https://github.com/user-attachments/assets/6cc1ee08-ea93-4cb3-a7f3-929b3623c271" />

### Outcome

Learned how Bash scripts automate Linux tasks by executing commands automatically and displaying output in the terminal.

## Session 3a – DNS & Digital Certificates

### DNS

I installed DNS utilities and tested domain name resolution using `nslookup` and `dig`.

<img width="651" height="526" alt="Screenshot From 2026-07-14 03-02-19" src="https://github.com/user-attachments/assets/f806c2d8-e002-4711-adb7-04db227aab08" />

<img width="651" height="526" alt="Screenshot From 2026-07-14 03-03-38" src="https://github.com/user-attachments/assets/817d40a8-005b-4d0d-8115-99aa1ecf5333" />


### Digital Certificates

I updated the system, installed Certbot, and verified an SSL/TLS certificate using OpenSSL.


<img width="651" height="526" alt="Screenshot From 2026-07-14 03-07-31" src="https://github.com/user-attachments/assets/787b3b42-5e0b-4db2-abda-38ebb79ff9e3" />


### Outcome

Learned how DNS translates domain names into IP addresses and how SSL/TLS certificates help provide secure encrypted communication between clients and servers.

## Session 3b – Server Automation

### Objectives

- Created a backup script using Bash.
- Scheduled the script using `cron`.
- Logged the script output to a file.
- Verified that the backup task executed successfully.

### Backup Script

I created a Bash script named `backup.sh` to automate the backup process. The script creates a backup directory, copies files, and records the execution time.

**Screenshot:** Backup script created using Nano.

### Automation Using Cron

I scheduled the backup script to run automatically using `crontab`. The script output was redirected to a log file for verification.

**Screenshot:** Cron job configured and backup log verified.

### Outcome

Successfully automated Linux backup tasks using Bash scripting and cron jobs. I learned how scheduled tasks help reduce manual work and improve server administration efficiency.

## Session 4a – Docker

### Objectives

- Installed Docker on Ubuntu.
- Verified the Docker installation.
- Executed the `hello-world` container.

### Docker Installation

I installed Docker on my Ubuntu virtual machine and verified the installation using the Docker version command.

**Screenshot:** Docker installation verified.

### Running the Hello World Container

I executed the `hello-world` container to confirm that Docker was working correctly.

**Screenshot:** Hello World container executed successfully.

### Outcome

Successfully installed Docker and verified that containers could run correctly. This provided practical experience with container-based applications and Docker fundamentals.
