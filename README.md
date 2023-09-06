## About

This Ansible Playbook is suitable to be used in ansible development and is tested on 
* RHEL 8
* RHEL 9 
* Fedora 38

environments. 

Based on https://gitlab.com/rgdacosta/classroom_env.git 

Big thanx to Ricardo da Costa, who is the origninal author and a great teacher.

## Contributing

If you have ideas or requests - mail me at tokitaari@mailbox.org

If you fancy contributing:

Create a branch -> Create a merge request -> Assign me as a reviewer.

## Getting started

Requires Ansible to be installed. 

```
git clone https://github.com/tokitaari/ansible_env.git

cd ansible_env

ansible-playbook playbook.yml
```

## Using

Check out these files for more information:

~/.bashrc

~/.vimrc

~/.tmux.conf

## Ansible aliases

These aliases are there to simplify your developing experience.

# Ansible Core

```
ap - ansible-playbook
apsc - ansible-playbook --syntax-check
acd - ansible-config dump
av - ansible --version
aig - ansible-inventory --graph
```

# Ansible Navigator

```
anr - ansible-navigator run -m stdout
ansc - ansible-navigator run -m stdout --syntax-check
anch - ansible-navigator run -m stdout --check
ancd - ansible-navigator config dump -m stdout
anv - ansible-navigator --version
anig - ansible-navigator inventory --graph
```

## Productivity aliases

pastebin - Fancy taking a file from the local environment to the Internet? `cat $file | pastebin`. It will provide you with a short URL to grab your file from your local system.
decomment - Strips a file (typically a config file) of comments


