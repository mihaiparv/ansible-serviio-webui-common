ansible-serviio-webui-common
========

Ansible role which installs [Serviio WebUI](http://kairoh.bitbucket.org/serviio-webui/), an alternate Serviio console
 you can access everywhere, from almost any desktop or mobile browser.

Role Variables
--------------

The variables that can be passed to this role and a brief description about
them are as follows:

    serviio_webui_version: '1.0.1-c'    # The version of serviio webui to install
    serviio_home: '/opt/serviio'        # The serviio home folder

Example Playbook
-------------------------

1) Install serviio

    - hosts: all
      roles:
      - ansible-serviio-webui-common

Dependencies
------------

The Serviio media server needs to be installed in `serviio_home`.

License
-------

BSD

Author Information
------------------

Parv Mihai