Role Name
=========

Installs Kubeadm

Requirements
------------

None

Role Variables
--------------

```
kubeadm_cgroup_driver: defaults to cgroupfs
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: solval.kubeadm

License
-------

Apache 2.0

Author Information
------------------

Jakub Dlugolecki
