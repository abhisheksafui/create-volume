Role Name
=========

Ansible role to create a volume, with option to specify backing image

Requirements
------------

NA

Role Variables
--------------

- image_size: 25G

- image_format: qcow2

- image_name: vm-ubuntu-1.qcow2

- pool: default

- backing_vol:  ubuntu_18.04_cloudimage.qcow2


Dependencies
------------

NA

Example Playbook
----------------

Check the tests/test.yml

License
-------

GPL-2.0

Author Information
------------------

Contact Abhishek Safui at abhishek6590@gmail.com
