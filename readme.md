# coreos-ansible

## Synopsis

* Install python, pip, docker, and docker-compose
* Deploy docker images with docker-compose

## Usage

### Use without inventory argument

#### Add hosts to inventory/core

    core-01 ansible_ssh_host=<host>

#### Edit /etc/ansible/ansible.cfg

    inventory = /path/to/inventory/core

#### Run ansible playbook

    ansible-playbook site.yml
    
### Run with inventory argument

    ansible-playbook -i /path/to/inventory/core site.yml