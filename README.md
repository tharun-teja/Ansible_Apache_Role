# Ansible_Apache_Role

Ansible automation to install, enable, and configure Apache with a sample index page.

## Quick Start

1. Update `inventory/hosts.ini` with your target servers
2. Run the playbook:
   ```bash
   ansible-playbook playbooks/site.yml

## Repository Structure
ansible-apache/
├── ansible.cfg
├── inventory/
│   └── hosts.ini
├── playbooks/
│   └── site.yml
└── roles/
    └── httpd/
        ├── tasks/
        │   └── main.yml
        ├── handlers/
        │   └── main.yml
        ├── templates/
        │   └── index.html.j2
        ├── defaults/
        │   └── main.yml
        └── meta/
            └── main.yml
