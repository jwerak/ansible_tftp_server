tftp_server
===========

This role installs and configures a tftp server.

Requirements
------------

This role requires Ansible 1.7 or higher and platform requirements are listed
in the metadata file.

Usage
-----
For example create ansible play file
```
- hosts: "tftp_server"
  roles:
  - role: tftp_server
    tftp_serve_files: [ 'ipxe.iso' ]
```
to serve file ipxe.iso which must be in `files/` dir.

Role Variables
--------------

## Basic configuration information
tftp_serve_files: array of files in files dir that should be served by tftp server

Dependencies
------------

None

License
-------

BSD

Author Information
------------------

Jakub Veverka
