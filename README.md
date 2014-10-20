# Ansible for twitch.city host

Goal: automate setting up a tilde-host?

## Before you can use Ansible

* git clone git://github.com/ansible/ansible.git --recursive
* sudo easy\_install pip
* sudo pip install paramiko PyYAML jinja2 httplib2

## Then, after cloning this repo
* export PATH=$PATH:/path/to/ansible/bin
* ansible-playbook -i inventory main.yml

## TODO
* https://registry.hub.docker.com/
* IRC, nntp, ...
