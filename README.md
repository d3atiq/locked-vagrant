locked-vagrant
==============

This ansible role ensures the vagrant user is locked, i.e. cannot login with a password. This is used to restrict access to the VM through the vagrant ssh console (and the respective SSH key pair).

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - locked-vagrant

License
-------

MIT

Author Information
------------------


