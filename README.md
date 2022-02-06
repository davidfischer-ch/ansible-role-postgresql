# Ansible Role PostgreSQL

Library of Ansible plugins and roles for deploying various services.
See [ansible-roles](https://github.com/davidfischer-ch/ansible-roles) for additional documentation.

This repository hosts the role PostgreSQL and may depend of other roles and plugins of the library.

## Dependencies

See [meta](meta/main.yml).

## Variables

TODO VARIABLES

## Example

### PlayBook

```
- hosts:
    - database
  roles:
    - postgresql
```

### Variables

```
postgresql_is_master: yes
postgresql_port: 5432
postgresql_version: 9.6
```

## License

See [LICENSE.rst](LICENSE.rst).

## Authors

See [AUTHORS](AUTHORS).

2014-2022 - David Fischer
