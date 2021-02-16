ZSH
=========

A personal role to install and configure ZSH. This role is not designed for publishing on Galaxy yet.

Requirements
------------

- `apt` for installation.
- `ansible` to apply the playbook.

Role Variables
--------------

No vaiable in play. The user and home is set via `{{ lookup('env','USER') }}`.

Dependencies
------------

- No other roles hosted on Galaxy are needed.

License
-------

MIT
