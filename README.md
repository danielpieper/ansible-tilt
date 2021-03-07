[![Build Status](https://travis-ci.com/danielpieper/ansible-tilt.svg?branch=main)](https://travis-ci.com/danielpieper/ansible-tilt)

Tilt
=========

This role installs [tilt](https://github.com/tilt-dev/tilt) in the users `.local/bin` directory.

Requirements
------------

TODO

Role Variables
--------------

TODO: A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

The `homebrew` role from the `community.general` collection is required.

Example Playbook
----------------

```
- hosts: localhost
  connection: local
  roles:
     - { role: danielpieper.tilt }
```

License
-------

MIT
