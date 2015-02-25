# Ansible security bootstrap

A full tutorial article can be found at: [Sécuriser son serveur avec Ansible](http://blog.octo.com/securiser-son-serveur-avec-ansible/)

## Setup

You need to install ansible on your computer : you can find documentation [here](http://docs.ansible.com/intro_installation.html)



## Configuration

Change the user/port/ip-address variables in [./production](production) file to suit your needs.


## Execute ansible

    ansible-playbook site.yml -i production --ask-sudo --ask-pass

