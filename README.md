# ansible-pull-demo

This repository is used for demonstration purpose of ansible-pull through cloud-init.
This repo contains only a simple dummy playbook to demonstrate how to install a simple web server with one simple html page

ansible-pull default behavior:
if no playbook is defined, then:
- look for `hostname`.yml playbook
- then fallback to local.yml
