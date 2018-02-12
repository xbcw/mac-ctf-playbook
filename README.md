# Mac CTF Ansible Playbook

This repository is a fork of Ricbra's excellent repository: https://github.com/ricbra/mac-dev-playbook which is a fork of Jeff Geerlings excellent repository: https://github.com/geerlingguy/mac-dev-playbook

It is a modified version suited to my needs.

For installation:
```
xcode-select --install
sudo easy_install pip
sudo pip install ansible
mkdir ${HOME}/Projects && cd ${HOME}/Projects
git clone git@github.com:xbcw/mac-ctf-playbook.git ${HOME}/Projects/mac-ctf-playbook
cd ${HOME}/Projects/mac-ctf-playbook
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory --ask-become-pass main.yml
```
