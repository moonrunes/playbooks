# Moon Runes Ansible Playbooks
Ansible Playbooks to deploy servers and clients including configurations and Docker Compose files

## Getting Started
1. Install Ansible
2. git clone this repository
3. Enable SSH on the remote systems
4. Add your systems IP address to *hosts.yml*
5. Run the requirements playbook using the password you specified while installing the server:

        ```ansible-playbook --inventory hosts.yml --ask-pass --ask-become-password requirements-playbook.yml```
6. Run the role playbook

## Things to add
- Ansible Pull configs?
- Automated updates
- Add FreeBSD/OpenWRT/Debian/Windows
