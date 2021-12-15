Cloud-Init Role
=========

This roles purpose is to remove the cloud-init package, service and network config.

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.cloudinit-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-cloudinit/)

Requirements
------------

All included in ansible-base package.

Role Variables
--------------

| Variable                | Required | Default | Choices                   | Comments                                 |
|-------------------------|----------|---------|---------------------------|------------------------------------------|
| cloudinit.cleanup       | yes      | false   | boolean value             | enable or disable this role              |

```yaml
cloudinit:
  cleanup: true
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - neoloc.cloudinit

License
-------

See license.md

Author Information
------------------

[![Github](https://img.shields.io/badge/Github-neoloc-blue.svg)](https://github.com/neoloc)
