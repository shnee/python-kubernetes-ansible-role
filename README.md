install_python_kubernetes: Ansible Role
================================================================================

An ansible role that installs the kubernetes python library via pip.

Requirements
----------------------------------------

This role requires that pip is installed on the remote machines. The
`python-kubernetes-ansible-role` is declared as a role dependency and will be
automatically installed.

Role Variables
----------------------------------------

None

Dependencies
----------------------------------------

See 'Requirements', the `python-kubernetes-ansible-role` is declared as a
dependency and will be ran bt this role.

Example Playbook
----------------------------------------

```yml
- hosts: all
  roles:
    - install_python_kubernetes
```

License
----------------------------------------

MIT

Author Information
----------------------------------------

This role was created by [shnee](https://github.com/shnee).
