# Project 02 - Ansible Playbook to Wnstall WordPress Development Environment
## Only for Debian or Ubuntu servers
- Installs the LAMP stack with a complete WordPress install

Install Ansible Galaxy collection and role for MySQL and WordPress
```
ansible-galaxy collection install community.mysql 
ansible-galaxy install oefenweb.wordpress
```

## Resources:
- https://docs.ansible.com/ansible/latest/collections/community/mysql/mysql_db_module.html
- https://galaxy.ansible.com/oefenweb/wordpress
