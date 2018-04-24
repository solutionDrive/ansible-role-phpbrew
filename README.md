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
List of requirements which should be installed with homebrew. See [here](https://github.com/phpbrew/phpbrew/wiki/Requirement#homebrew)

```
phpbrew_linked_requirements:
  - icu4c
  - openssl
  - libxml2
```
List of requirements which should be linked with homebrew. See [here](https://github.com/phpbrew/phpbrew/wiki/Requirement#homebrew)

```
phpbrew_install_version: "1.23.1"
```
Version which should be installed

```
phpbrew_releases_url: "https://github.com/phpbrew/phpbrew/raw/{{ phpbrew_install_version }}/phpbrew"
```
Url to download phpbrew

```
phpbrew_download_destination: "/tmp/phpbrew_{{ phpbrew_install_version }}"
```
Path which will be used to download phpbrew

```
phpbrew_execution_path: "/usr/local/bin/phpbrew"
```
Path which will be used to make phpbrew executable

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
