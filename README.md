Role Name: Docker
=========

An Ansible role for installing Docker and Docker Compose for Ubuntu.

Requirements
------------

None.

Role Variables
--------------

```bash
user: username

prereqpackages:
  - curl
  - apt-transport-https
  - ca-certificates
  - software-properties-common

dockerpackages:
  - docker-ce
  - docker-ce-cli
  - containerd.io
  - docker-compose

commonpackages:
  - neovim
  - htop
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - docker

License
-------

BSD

Author Information
------------------

This role was created in 2025 by sixstorm.  A bored, weathered Windows SysAdmin.