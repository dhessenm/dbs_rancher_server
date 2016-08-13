Role Name
=========

Role installs rancher server.

Requirements
------------

Running Docker engine ist required on host.


Role Variables
--------------

Available variables are listed below, along with default values:

* rancher_name: ranger_server (Docker container name)
* rancher_port: 8080 (Ranger port mappt on host)


Dependencies
------------

Example Playbook
----------------

    - hosts: rancherhost
      roles:
         - dbs_docker
         - dbs_rancher_server

License
-------

BSD

Author Information
------------------
it's me
