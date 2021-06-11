OS Requirements
===============
> apt install sshpass

Install Ansible Requirements
============================
ansible-galaxy install -r requirements.yaml

How to run it
=============
ansible-playbook play.yaml -i inventory.yaml --ask-vault-pass --skip-tags arm

Edit Vault Variables
====================
ansible-vault edit group_vars/pi/vault.yaml
