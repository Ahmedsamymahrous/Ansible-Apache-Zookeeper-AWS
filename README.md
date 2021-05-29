# Ansible playbook to install Apache Zookeeper cluster on AWS
Ansible playbook that installs Apache Zookeeper in three EC2 on AWS and configures every EC2 to have a different ID and run it as a service

## Run The Playbook
```sh
   ansible-playbook -i hosts playbook.yml --private-key <PRIVATE_KEY_FILE>
```
