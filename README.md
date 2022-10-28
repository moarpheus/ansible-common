# Ansible playbook for Centos/RHEL 8

Provisions users alongside with their encrypted passwords and id_rsa.pub keys. 

Intstalls following epel repo and following tools:

* curl
* nss
* git
* ncdu
* htop
* crontabs


Use following command on any linux machine to encrypt your *password*.

    perl -e 'print crypt("password","\$6\$saltsalt\$") . "\n"'
