# Linux Development Environment Ansible Playbook 

This playbook installs and configures most of the software I use on my Linux computer (PopOS) for software development. 
This is a work in progress at all times. You can use this repo as an inspiration for your own setup, using it without 
any adjustments won't really be useful to you.

## Installation

### Preparation Steps for PopOS 22.04

1. `sudo apt install python3-pip`
2. `pip3 install ansible`
3. `sudo apt install ansible`

### Using this playbook

1. Clone or download this repository to your local drive.
2. Run `ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
3. Run `ansible-playbook main.yml --ask-become-pass` inside this directory. Enter your sudo password when prompted for the 'BECOME' password.
