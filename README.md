tftp_server
===========

This role installs and configures a tftp server.

Requirements
------------

This role requires Ansible 1.7 or higher and platform requirements are listed
in the metadata file.

Role Variables
--------------

The variables that can be passed to this role and a brief description about
them are as follows. These are all based on the configuration variales of the
DHCP server configuration.

    # Basic configuration information
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
