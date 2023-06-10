[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/swapfile.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/swapfile)

Role Description
=========

Create swapfile.

Requirements
------------

None

Role Variables
--------------

```YAML
swapfile_path: Path of the swap file to create
swapfile_size: Size of the file. See details community.general.filesize module manual.
swapfile_blocksize: Size of blocks.
```

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - swapfile
```

License
-------

BSD
