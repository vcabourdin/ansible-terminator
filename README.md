Role Name
=========

Terminator installation on Debian/Ubuntu

Requirements
------------

Ruby

Role Variables
--------------

terminator_config_path: "~/.config/terminator/"
> Be careful that it will copy the base configuration file in the user home directory, so if you run this playbook as root it will be copied in root's home

Dependencies
------------

None

Example Playbook
----------------

Simplest way to include this role to your playbook :

    - hosts: servers
      roles:
         - { role: vcabourdin.terminator }

License
-------

MIT

Author Information
------------------

I would be happy to **adapt this role to other platforms**. If you are interested in such feature, please [create an issue](https://github.com/vcabourdin/ansible-terminator/issues/new) or, even better, a pull request :)
