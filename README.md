[![Build Status](https://travis-ci.org/midonet/ansible-midonet-repos.svg?branch=master)](https://travis-ci.org/midonet/ansible-midonet-repos)
[![Build Status](https://drone.io/github.com/midonet/ansible-midonet-repos/status.png)](https://drone.io/github.com/midonet/ansible-midonet-repos/latest)

Role Name
=========

Ansible playbook for midonet OSS repositories.

Installation
------------

This role requires at least Ansible v1.6

    ansible-galaxy install abelboldu.midonet-repos

Role Variables
--------------

Default variables:

    --

    midonet_version   : current
    midonet_release   : stable
    openstack_version : juno
    plugin_release    : stable


Example Playbook
----------------

    - hosts: server
      roles:
         - role: abelboldu.ansible-repos
		   midonet_version: 2015.03

License
-------

Apache 2.0

