extendi.nodenv
=========

Install nodenv on Ubuntu

Requirements
------------

None

Role Variables
--------------

    extendi_nodenv_version: 10.5.0

node version to install

    extendi_nodenv_user: root

install nodenv for this user

    extendi_nodenv_add_to_path: true

add nodenv to path

    extendi_nodenv_packages: []

nodenv packages to install

Dependencies
------------

None

Example Playbook
----------------

    - hosts: nodenv-servers
      roles:
         - extendi.nodenv

Author Information
------------------

This role was created in 2019 by [Domenico Commisso](mailto:commisso@extendi.it)
