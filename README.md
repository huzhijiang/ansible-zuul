Ansible Zuul
============

Ansible role for deploying Zuul

_Tested on RHEL 7_

Requirements
------------

None.

Dependencies
------------

None.

Role Variables
--------------

| Name            | Default                           | Description                               |
|-----------------|-----------------------------------|-------------------------------------------|
| gerrit_server   | None                              | Gerrit server url                         |
| gerrit_user     | None                              | Gerrit user                               |

Example Playbook
----------------

    - hosts: node
      roles:
        - role: ansible-zuul

License
-------

Apache

Author Information
------------------

Arie Bregman - abregman@redhat.com
