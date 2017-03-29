[![Build Status](https://travis-ci.org/godleon/ansible-role-kvm_host.svg?branch=master)](https://travis-ci.org/godleon/ansible-role-kvm_host)

Role Name
=========

Deploy KVM virtualization environment with VLAN support (integrated with Open vSWitch and Linux Bonding mode 6)

For the time being the following platforms are supported:

- [Ubuntu 16.04(Xenial)](http://releases.ubuntu.com/16.04/)


Requirements
------------

If you want to provision this role to [Ubuntu 16.04(Xenial)](http://releases.ubuntu.com/16.04/), please follow below instructions to install python 2.7 for Ansbile provision:

> sudo apt-get update && sudo apt-get -y install python2.7

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
