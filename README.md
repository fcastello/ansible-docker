ansible-docker
=========

A playbook to install docker in ubuntu based OS.

Requirements
------------

- Ubuntu installed (tested with 18.04)

Role Variables
--------------

None Yet

Example Playbook
----------------
```yaml
- hosts: all
 - name: Docker
    import_role:
      name: fcastello.docker
```

To Do
-----

- Change the default docker path
- Add a customizable docker config
- Add a way to pin to specific version
- Docker configuration without iptables
- Change default subnet to docker0 bridge
- Add a way to configure multiple bridges

Limitations
-----------
- Tested only in ubuntu 18.04. It should work in newer versions too but hasnt been tested.
- Might work in other Debian based distributions but has not been tested.
- has been tested with amd64 and arm64 architectures. 


License
-------

MIT

