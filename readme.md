## coreos-ansible

### Synopsis

* Install python, pip, docker, and docker-compose
* Deploy docker images with docker-compose

### Usage

Add hosts to inventory/core

    core-01 ansible_ssh_host=<host>

Edit /etc/ansible/ansible.cfg

    inventory = /path/to/inventory/core

AND Run ansible playbook

    ansible-playbook site.yml
    
OR run with inventory argument

    ansible -i /inventory/core site.yml