# Ansible for twitch.city host

Goal: automate setting up a tilde-host?

## Before you can use Ansible

* git clone git://github.com/ansible/ansible.git --recursive

## Then: (Required for Ansible):
* sudo easy\_install pip
* sudo pip install --upgrade six
* sudo pip install paramiko PyYAML jinja2 httplib2 docker-py

## Then, after cloning this repo
* export PATH=$PATH:/path/to/ansible/bin
* ansible-playbook -i inventory main.yml

## TODO
* different /etc/skel repo
* install: zsh, csh, tcsh, fish (requires new repo, how to do with ansible?)
* rrdtool, jq
* mg vile zile (editors)
* slrn is a problem, must be manually done. 
* talk-server
* postfix ?
* others from: https://github.com/tildeclub/tilde.club/blob/master/docs/server.org
