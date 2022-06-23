# Linux Development Environment Ansible Playbook 

This playbook installs and configures most of the software I use on my Linux computer (PopOS) for software development. 
This is a work in progress at all times. You can use this repo as an inspiration for your own setup, using it without 
any adjustments won't really be useful to you.

## Installation

1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html):
2. Clone or download this repository to your local drive.
3. Run `ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
4. Run `ansible-playbook main.yml --ask-become-pass` inside this directory. Enter your sudo password when prompted for the 'BECOME' password.
