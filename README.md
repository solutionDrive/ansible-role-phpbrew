phpbrew
=======

Install phpbrew on mac osx

Requirements
------------

homebrew

Role Variables
--------------

```
phpbrew_requirements:
  - automake 
  - autoconf 
  - curl 
  - pcre 
  - bison 
  - re2c 
  - mhash 
  - libtool 
  - icu4c 
  - gettext 
  - jpeg 
  - openssl 
  - libxml2 
  - mcrypt 
  - gmp 
  - libevent
```
List of requirements which should be installed with homebrew. See [here](https://github.com/phpbrew/phpbrew/wiki/Requirement)

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: 127.0.0.1
      connection: local
      roles:
         - { role: solutionDrive.phpbrew }

License
-------

See LICENSE file

Author Information
------------------

This role was created by [solutionDrive](https://solutiondrive.de)
