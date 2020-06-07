# ElasticSearch Ansible

This is ansbile playbook for elasticsearch only


## Install role

`$ ansible-galaxy install elastic.elasticsearch,7.7.1`

## Run ansible-playbook

`$ ansible-playbook -i inventory.cfg elasticsearch.yaml -b --extra-vars "ansible_sudo_pass=YOURSUDOPASS"`

# Copyright

2020 Suhendra Ahmad
