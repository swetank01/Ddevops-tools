# Ansible 


### Setup 


### Demo
eval $(ssh-agent)
ssh-add ansible-node 
ansible -i hosts -m ping all


## Documentation from "Ansible For Php Dev"

$ touch site.yml
$ mkdir roles
$ cd roles
$ ansible-galaxy init php
$ ansible-galaxy init mysql
$ ansible-galaxy init nginx
$ ansible-galaxy init common
$ ansible-galaxy init acl