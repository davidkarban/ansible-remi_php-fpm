remi_php-fpm
=========

PHP fpm installation from REMI repository.

Requirements
------------

Remi repository. Can be downloaded via davidkarban.remi_repo galaxy role.
Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

php_version: Version of php to install.

Dependencies
------------

davidkarban.remi_repo

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: remi_php-fpm, php_version: "php56" }

License
-------

GPLv3

Author Information
------------------

David Karban - david@karban.eu - www.karban.eu - https://github.com/davidkarban

