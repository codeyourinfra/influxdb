# influxdb

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub release](https://img.shields.io/github/release/codeyourinfra/influxdb.svg)]() [![Build status](https://travis-ci.org/codeyourinfra/influxdb.svg?branch=master)](https://travis-ci.org/codeyourinfra/influxdb)

Ansible role to install [InfluxDB](https://www.influxdata.com/time-series-platform/influxdb).

## Example Playbook

```yml
---
- hosts: servers
  roles:
    - codeyourinfra.influxdb
```

The role requires the *ansible_distribution_release* variable, obtained through the [gathering facts phase](https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#information-discovered-from-systems-facts). So please don't turn off facts.

## Build process

The build process is performed in [Travis CI](https://travis-ci.org/codeyourinfra/influxdb). During the build, the role is tested by using [Ubuntu Docker images with Python 3](https://hub.docker.com/r/codeyourinfra/python3).

## Author Information

[@gustavomcarmo](https://github.com/gustavomcarmo) is a contributor of [Codeyourinfra](https://github.com/codeyourinfra). Get on board too! :)
