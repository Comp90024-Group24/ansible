# Ansible code
This project will be developed and used based on the Melbourne Research Cloud. The process and implementation of the project will be described below.<br>
Project: Unimelb COMP90024 - Automate deploy<br>
Author: jiyuan Chen 1323889<br>

## File Structure Description
<pre>
.
├── host_vars/
│   ├── config.yaml #Variable name
├── inventory/
│   ├── hosts.ini #host name
├── roles/
│   ├── deploy-backend/tasks
│   ├── deploy-docker/tasks
│   ├── deploy-frontend/tasks
│   ├── deploy-git/tasks
│   ├── deploy-harvester-git/tasks
│   ├── deploy-harvester-instance/tasks
│   ├── deploy-harvester/tasks
│   └── deploy-harvester/taskspre-install/tasks
├── README.md
├── ansible-backend.sh
├── ansible-frontend.sh
├── ansible-harvester.sh
├── cloud_key.pem
├── openrc.sh
├── run.sh
├── setup-backend.yaml
├── setup-frontend.yaml
├── setup-harvester.yaml
└── setup.yaml
</pre>
## File Structure Description
![image](https://github.com/Comp90024-Group24/ansible/assets/61899807/5b2e43f8-c609-41f8-a516-06d68a9c6845)




