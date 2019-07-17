# ansible-wrf-v4
Automated installation of [WRF V4.0](http://www2.mmm.ucar.edu/wrf/OnLineTutorial/compilation_tutorial.php) on CentOS 7

Role Name
=========

An Ansible Role that installs WRF V4.0 on Linux CentOS 7

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```yaml
USER: yourusername
```

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: username.rolename, x: 42 }


Running a Playbook
------------------

```sh
$ ansible-playbook -i hosts playbook.yml -K -k -b -v
```

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by [João Carlos Mendes](https://br.linkedin.com/in/jcarlosmendesti)