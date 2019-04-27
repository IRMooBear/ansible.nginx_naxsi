Nginx Naxsi
=========
This role download and compile the Naxsi Web Application Firewall module for Nginx as a dynamic module for configure it.

Still a WIP, DO NOT USE!

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Dependencies
------------
- irmoobear.nginx

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: irmoobear.nginx }

License
-------
BSD

Author Information
------------------
An optional section for the role authors to include contact information, or a website (HTML is not allowed).