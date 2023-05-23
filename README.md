# Ansible code
This project will be developed and used based on the Melbourne Research Cloud. The process and implementation of the project will be described below.<br>
Project: Unimelb COMP90024 - Automatic Deploy<br>
Author: jiyuan Chen 1323889<br>

# File Structure Description
<pre>
.
├── host_vars/
│   ├── config.yaml #Variable name
├── inventory/
│   ├── hosts.ini #host name
├── roles/
│   ├── deploy-backend/tasks   #deploy backend yaml file  
│   ├── deploy-docker/tasks    #deploy docker yaml file  
│   ├── deploy-frontend/tasks  #deploy frontend yaml file  
│   ├── deploy-git/tasks       #git clone yaml file  
│   ├── deploy-harvester-git/tasks  #git harvester yaml file 
│   ├── deploy-harvester-instance/tasks    #create harvester instance yaml file 
│   ├── deploy-harvester/tasks   #deploy harvester yaml file 
│   └── pre-install/tasks   #deploy related environment yaml file 
├── README.md
├── ansible-backend.sh 
├── ansible-frontend.sh
├── ansible-harvester.sh
├── cloud_key.pem      #ssh key
├── openrc.sh          #Melbourne Research Cloud OpenStack
├── run.sh
├── setup-backend.yaml
├── setup-frontend.yaml
├── setup-harvester.yaml
└── setup.yaml
</pre>
# System Architecture Diagram
![image](https://github.com/Comp90024-Group24/ansible/assets/61899807/5b2e43f8-c609-41f8-a516-06d68a9c6845)
# System run
## When deploying the back-end environment, the following commands need to be executed:<br>
##  `./ansible-backend.sh`
## When deploying the back-end environment, the following commands need to be executed:<br>
##	`./ansible-frontend.sh`
## When deploying the back-end environment, the following commands need to be executed:<br>
##  `./ansible-harvester.sh`
## On the current localhost for deploying the whole system automatically, the following commands need to be executed:<br>
##   `./run.sh`







