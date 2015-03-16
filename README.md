# Ansible Role: Nginx

[![Build Status](https://travis-ci.org/Aplyca/ansible-role-nginx.svg?branch=master)](https://travis-ci.org/Aplyca/ansible-role-nginx)
[![Circle CI](https://circleci.com/gh/Aplyca/ansible-role-nginx.png?style=badge)](https://circleci.com/gh/Aplyca/ansible-role-nginx)

Ansible Role that installs an configure Nginx on Debian/Ubuntu.

## Requirements

Use hash behavior for variables in ansible.cfg
See example: https://github.com/Aplyca/ansible-role-nginx/blob/master/tests/ansible.cfg
See official docs: http://docs.ansible.com/intro_configuration.html#hash-behaviour

## Installation

Using ansible galaxy:
```bash
ansible-galaxy install mauricios.Nginx
```
You can add this role as a dependency for other roles, add the role to the meta/main.yml file of your own role:
```yaml
dependencies:
  - { role: mauricios.Nginx }
```

## Role Variables

See default variables: https://github.com/Aplyca/ansible-role-nginx/blob/master/defaults/main.yml

## Dependencies

None.

## Testing

Use Vagrant to test the role:

```bash
cd tests;
vagrant up;
```
You should see an Nginx server on http://ansible.apache

## License

MIT / BSD

## Author Information

Mauricio Sánchez from Aplyca SAS (http://www.aplyca.com)
