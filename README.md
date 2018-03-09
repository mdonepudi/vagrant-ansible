# Vagrant - Ansible - Docker
This repository demonstrates how to:
 - Bootstrap [CentOS/7](https://app.vagrantup.com/centos/boxes/7) Vagrant box
 - Provision the guest using Ansible playbook
    - Install Docker Service
    - Launch NGINX container [nginx:alpine](https://hub.docker.com/_/nginx/)
 - Serve static content from NGINX container on host name (port 8080) 


### Requirements
To use this demo repo, host machine requires [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html) and [Vagrant](https://www.vagrantup.com/docs/installation/)

### Installation and Usage
Simply clone this repository on to the machine:

```
git clone https://github.com/mdonepudi/vagrant-ansible.git
```

Start the machine using Vagrant up command

```
vagrant up
```

Access the webpage using the machine IP or localhost:8080

```
http://127.0.0.1:8080
```
### Troubleshooting

ERROR: No usable default provider could be found for your system.

CAUSE: Vagrant requires virtualmachine providers like VirtualBox, VMware etc.

SOLUTION: Install virtualbox

