jbgo.ansible
============

Install Ansible with Ansible! This role installs an Ansible control node

Variables
--------------

| var | description | default |
|-----|-------------|---------|
| ansible_user | The control node user for running Ansible playbooks | deploy |

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jbgo.ansible, ansible_user: ansible, become: yes }

License
-------

MIT - see [LICENSE.txt](https://github.com/jbgo/ansible-ansible/blob/master/LICENSE.txt)

Author Information
------------------

[Jordan Bach](https://opensolitude.com)
