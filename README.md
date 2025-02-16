Ansible Project

Introduction

This project uses Ansible for server automation, configuration management, and deployment.

Prerequisites

Install Ansible (pip install ansible or sudo apt install ansible)

SSH access to target servers

Python 3

Project Structure

├── inventory.ini      # List of managed hosts
├── playbook.yml       # Ansible playbook
├── ansible.cfg        # Configuration file
└── README.md          # Documentation

Running the Playbook

ansible-playbook -i inventory.ini playbook.yml

Test connectivity with ansible -i inventory.ini all -m ping

Verify SSH key setup