==
Ansible wordpress setup
==

# How to use
Make sure you have installed Ansible
```
brew install Ansible
brew install git
git clone https://github.com/vikas17a/ansible-wordpress.git
cd ansible-wordpress/playbooks
#Update hosts for you and make sure your key is there on machine also update ansible-wordpress/group_vars/test/ansible_ssh_user
ansible-playbook wordpress.yml -i ../hosts
```
