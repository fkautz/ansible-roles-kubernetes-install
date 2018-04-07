Kubernetes
=========

Installs Kubernetes

Requirements
------------

RHEL or Ubuntu

Role Variables
--------------

kubernetes_version: 1.10.0

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: fkautz.kubernetes, kubernetes_version: 1.10.0 }

License
-------

Apache License V2

Author Information
------------------

Frederick F. Kautz IV - Red Hat
