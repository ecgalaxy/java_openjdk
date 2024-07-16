ECGALAXY java_openjdk role
===========================

This Ansible role installs Java OpenJDK (default Java version: 11).

Requirements
------------

None.

Role Variables
--------------

- `java_version`: 11

Available values per platform:

Amazon Linux 2

- 11
- 17

Amazon Linux 2023

- 1.8.0
- 11
- 17
- 21
- 22

RHEL 8 & 9

- 1.8.0
- 11
- 17
- 21
- latest

Ubuntu 18.04

- 8
- 11
- 17

Ubuntu 20.04

- 8
- 11
- 13
- 16
- 17
- 21

Ubuntu 22.04

- 8
- 11
- 17
- 18
- 19
- 21

Ubuntu 24.04

- 8
- 11
- 17
- 21

Dependencies
------------

* optional: ecgalaxy.bootstrap

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.java_openjdk

One-liner
---------

    bash <(curl -s https://code.europa.eu/-/snippets/1/raw/main/ansible-role.sh) ecgalaxy.java_openjdk

See [ansible-role](https://code.europa.eu/-/snippets/1) for instructions.

Please verify the script integrity first.

Upgrading & Uninstalling
------------------------

This Ansible role uses the distribution's package manager to install packages.

In order to upgrade or uninstall a package, please refer to your distribution's package manager documentation.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

[ECGALAXY](https://code.europa.eu/groups/ecgalaxy/-/wikis/home) team.
