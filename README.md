andrewrothstein.airflow
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-airflow.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-airflow)

Installs [airflow](https://airflow.incubator.apache.org/index.html) into a conda environment.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.airflow
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
