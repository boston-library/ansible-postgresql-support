# ansible-postgresql-support

An Ansible role for installing libraries that support the following PostgreSQL Ansible modules:

- [postgresql_db](http://docs.ansible.com/postgresql_db_module.html)
- [postgresql_user](http://docs.ansible.com/postgresql_user_module.html)

## Role Variables

- `postgresql_support_libpq_version` - PostgreSQL client library version (default: `9.5.*.pgdg14.04+2`)
- `postgresql_support_psycopg2_version` - Psycopg2 version (default: `2.6`)
- `postgresql_support_repository_channel` - PostgreSQL repository channel (default: `9.5`)

## Reference

This ansible role is taken mostly out of [ansible-postgresql-support](https://github.com/azavea/ansible-postgresql-support.git) from Azavea Inc., but I stripped it down for brevity.

