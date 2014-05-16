aspects_common_packages
========
Part of the Aspects Suite.

Easy installation of packages accross multiple OS families. 

Requirements
------------

Set ```hash_behaviour=merge``` in your ansible.cfg file.

Role Variables
--------------
TODO: Describe vars.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - aspects_common_packages
      vars:
        aspects_common_packages:
          ssh:
            state: "latest"
          htop:
            state: "absent"

License
-------

MIT
