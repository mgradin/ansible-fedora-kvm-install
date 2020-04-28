Role Name
=========

Install and configure libvirt.

Requirements
------------

* Ansible to run this role.
* Fedora installation to install and configure on.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

- hosts: srv01
  roles:
    - role:  ansible-fedora-kvm-install
      tags: [ kvm ]
      become: yes

License
-------

BSD

Author Information
------------------
* Mathias Gradin - mgradin@gmail.com
