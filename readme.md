## coreos-ansible

### Synopsis

* Install python, pip, docker, and docker-compose
* Deploy docker images with docker-compose

### Usage

Add hosts to inventory/core
    
    ansible-playbook -i inventory/core site.yml