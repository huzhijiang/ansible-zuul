Ansible Zuul
============

Ansible role for deploying Zuul

_Tested on RHEL 7_

Requirements
------------

User should have sudo on the target system.

Dependencies
------------

None.

Role Variables
--------------

| Name            | Default                | Description                           |
|-----------------|------------------------|---------------------------------------|
| gerrit_server   | 127.0.0.1              | FQDN of Gerrit server                 |
| gerrit_user     | zuul                   | User to use when logging to Gerrit    |
| gerrit_sshkey   | /home/zuul/.ssh/id_rsa | SSH key path, for logging into Gerrit |
| gerrit_port     | 29418                  | Gerrit server port                    |
| zuul_layout     | None                   | Zuul layout file                      |



Example Playbook
----------------

    - hosts: node
      roles:
        - role: ansible-zuul

Note: you can copy the sample from playbooks directory.

License
-------

Apache

Author Information
------------------

Arie Bregman - abregman@redhat.com
