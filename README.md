mate_desktop
============

An Ansible role to install the MATE Desktop on Red Hat distributions, i.e. CentOS 8, CentOS 7 and Fedora. RHEL is not tested, but should work. On CentOS 8, as no EPEL MATE package exists, the [official unofficial repository for MATE for EL8](https://copr.fedorainfracloud.org/coprs/stenstorp/MATE/) is used.

*Note that since I wrote this role I stopped using MATE, so I'm not likely to spend much time maintaining it. If you would like to take over the project, let me know.*

Requirements
------------

This role is meant to be used on a graphical workstation type of installation.

Role Variables
--------------

None.

Dependencies
------------

The [repo-epel](https://galaxy.ansible.com/geerlingguy/repo-epel) role is used to install the EPEL repository on CentOS.

Example Playbook
----------------

    - hosts: workstations
      roles:
        - nmusatti.mate_desktop

License
-------

GPLv3

Author Information
------------------

Nicola Musatti - https://github.com/nmusatti
