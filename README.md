# Mac Development Ansible Playbook

This repository is a fork of Jeff Geerlings excellent repository: https://github.com/geerlingguy/mac-dev-playbook
It is a stripped version suited to my needs.

For installation:
```
xcode-select --install
sudo easy_install pip
sudo pip install ansible
mkdir ~/Projects && cd ~/Projects
git clone git@github.com:xbcw/mac-ctf-playbook.git
cd mac-ctf-playbook
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory --ask-become-pass main.yml
```
