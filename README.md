# AnsibleBootstrap
An Ansible playbook wich permits to bootstrap Ansible on a bunch of servers from an Ansible Master with Ansible :)

When you have to "connect" a server to an Ansible Master you can find easily some "recipes"
which show how to:
- verify if sudo is installed on target servers
- create a specific Ansible user on target servers
- add the specific Ansible user in suoders
- copy the public ssh key of the specific Ansible user on target servers

You can do these actions with shell scripts, or with Ansible ad-hocs commands.

But with this playbook, you can do it directly with ansible-playbook.
