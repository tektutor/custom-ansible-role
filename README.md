Role Name
=========

This is a role that installs Apache web server, configures document root and deploys custom web page.

Requirements
------------
You need ansible nodes. As of now only Ubuntu 16.04 and CentOS 8.3 platforms are supported.

Role Variables
--------------
You may configure provisioner_tool, greeting_msg and conf_mgr_tool.

Dependencies
------------
This role doesn't depend on any other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - apache 

License
-------

Apache 2.0

Author Information
------------------
Jeganathan Swaminathan <jegan@tektutor.org>
