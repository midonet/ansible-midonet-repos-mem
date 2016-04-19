ansible-midonet-repos-mem
=========================

Ansible playbook for Midonet MEM repositories.

Installation
------------

This role requires at least Ansible v1.6

    ansible-galaxy install midonet.midonet-repos-mem

Role Variables
--------------

Default variables:

    --
    mem_version   : 5
    mem_release   : stable


Also, `mem_user` and `mem_password` variables are required to access MEM private
repositories.

Contact [Midokura](http://www.midokura.com/about-midokura/contact)  to get your credentials.

Example Playbook
----------------

    - hosts: server
      roles:
        - role: midonet.midonet-repos-mem
          mem_user: BobDobbs
          mem_password: DemoPassword

License
-------

Apache 2.0
