# Ansible playbook to install Apache Zookeeper cluster on AWS
Ansible playbook that install Apache Zookeeper in three EC2 on AWS and configure every EC2 to have different ID and run it as a service

## Run The Playbook
```sh
   ansible-playbook -i hosts playbook.yml --private-key aws_private_key.pem
```
