# install-lampstack
Install complete LAMP stack just one click

This Ansible playbook would install Epel repo along w/ remi-php repo and would enable whatever version of php you wants to enable just make that changes into vars file.

Step 1:
Just change your hosts into hosts

Step 2:
choose your PHP version e.g. PHP 7.0, 7.1, 7.2, 7.3, 7.4

Step 3:
Just play your playbook

e.g. ansible -m ping -i inventory/hosts aws  it should return "PONG" as success

Run Playbook
ansible-playbook -i inventory/hosts install-apache-php-centos8.yaml
