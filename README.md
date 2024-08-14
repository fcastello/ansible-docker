ansible-docker
=========

A playbook to install docker in ubuntu based OS.

Requirements
------------

- Ubuntu installed (tested with 18.04 and ubuntu 20.04)

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

- Add a way to pin to specific version
- Change default subnet to docker0 bridge
- Add a way to configure multiple bridges

Limitations
-----------
- Tested only in ubuntu 24.04. It should work in newer versions too but hasn't been tested. I might work with 18.04, 20.04 and 22.04 but without any guarantees 
- Might work in other Debian based distributions but has not been tested.
- has been tested with amd64 and arm64 architectures. 


License
-------

MIT

