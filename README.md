# Project 02 - Setup a LAMP stack server with a complete WordPress install using Ansible

Steps to install Ansible Galaxy collection and role for MySQL and WordPress
```
ansible-galaxy collection install community.mysql 
ansible-galaxy install oefenweb.wordpress
```

### Note:
* Only works on Debian or Ubuntu machines

### Resources:
- https://docs.ansible.com/ansible/latest/collections/community/mysql/mysql_db_module.html
- https://galaxy.ansible.com/oefenweb/wordpress
- https://www.digitalocean.com/community/tutorials/how-to-use-ansible-to-install-and-set-up-wordpress-with-lamp-on-ubuntu-18-04
