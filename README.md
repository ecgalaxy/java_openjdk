ECGALAXY java_openjdk role
===========================

Installs Java OpenJDK.

Requirements
------------

None.

Role Variables
--------------

- `java_version`: 11

Available values per platform:

Amazon Linux 2

- 1.7.0
- 1.8.0
- 11
- 17

RHEL 8

- 1.8.0
- 11
- 17
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

Dependencies
------------

* optional: ecgalaxy.bootstrap

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.bootstrap
        - ecgalaxy.java_openjdk

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
