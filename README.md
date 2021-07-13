Role Name
=========

This role is to install the network drivers update on the xenserver host 

Requirements
------------

You need to deploy the role on the xenserver hosts with access to internet to download the files. 

Role Variables
--------------

Username and password for downloading the drivers from the citrix site and the URL of the required drivers.

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
