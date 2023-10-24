# Eth-Hack Lab Creation
This project is to buikd targets for eth-hack students at Champlain College. 

## Why
This provides further learning opportunities for myself as I have not created vulnerable targets before as well as providing challenges for furture eth-hack students.

## Features/Objectives
- Creation of windows tragets to be used
- making sure they are attackable
- they are easy to reset
- the setup could be automated (requires learning ansible)

# Project Mindmap (image + outline) 
Mindmap Link: https://drive.google.com/file/d/1g7jFDOtJWtXNKtvjue2bA-jywMf6Pza4/view?usp=sharing

![image](https://github.com/jude-lindale/Capstone-Project/assets/70959569/1c396783-9903-42a0-bcab-2c7cbf184789)

     Eth-Hack II targets
     ├── vSphere/VMware product to build out vms
     |   ├── targets
     |   |   ├── Windows 2019 Server
     |   |   |   ├──	2 CPUs
     |   |   |   ├── 4 GB memory
     |   |   |   ├──60 GB hard disk
     |   |   |   ├── vulnerability to gain access to environment
     |   |   |   |   └── Vulnerability yet to be determaned
     |   |   |   ├── vulnerability to gain admin access
     |   |   |   |     └── Vulnerability yet to be determaned
     |   |   |   ├── AD server
     |   |   |   ├── Environment Admin account
     |   |   |   └── 64 Bit
     |   |   ├── Windows 10
     |   |   |   ├── 64 Bit
     |   |   |   ├── 2 CPUs
     |   |   |   ├── 4 GB memory
     |   |   |   ├── 32 GB hard disk
     |   |   |   ├── Normal Privilege user (admin user on webserver)
     |   |   |   ├── Admin user
     |   |   |   ├── vulnerability to gain admin access
     |   |   |   |   └── Vulnerability yet to be determaned
     |   |   |   ├── Windows 10 used to get access to AD server
     |   |   |   └── SSH
     |   |   └── Windows 10 webserver
     |   |       ├── 64 bit
     |   |       ├── 2 CPUs
     |   |       ├── 4 GB memory
     |   |       ├── 32 GB hard disk
     |   |       ├── webserver with user login info
     |   |       ├── Vuln within web server allowing admin access
     |   |       |   └── Vulnerability yet to be determaned
     |   |       └── Webserver is used to get to windows 10 target
     |   |           └──SSH
     |   |       
     ├── Documentation
     |   ├── Environment configuration
     |   |   └── vulnerability setup
     |   └── ansible code build for automated setup
     |        └── Exploitation walk through
     └──  Environment setup automation
     └── Learn ansible Windows environment automation
     └── Create scripts to automate setup for each vm
