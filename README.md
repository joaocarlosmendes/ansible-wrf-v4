# ansible-wrf-v4
Automated installation of [WRF V4.0](http://www2.mmm.ucar.edu/wrf/OnLineTutorial/compilation_tutorial.php) on CentOS 7

common
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

- See [documentation](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) for Ansible installation 

Tips
----

- Do not use the root user, use a regular user and add him as a superuser before running this role.

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by [João Carlos Mendes](https://br.linkedin.com/in/jcarlosmendesti)
