require_implicity_localhost
=========

This role asserts that `localhost` is not in the inventory file.

Before ansible 2.3, to get the correct current local python interpreter,
the `localhost` should not be in the inventory file, 
and use `delegate_to: localhost` to run a moudle locally.

Requirements
------------

Ansible >= 1.5 for `assert` module

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - gzm55.require_implicity_localhost

License
-------

BSD
