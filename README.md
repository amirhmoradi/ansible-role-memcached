# ansible-role-memcached

Install and configure Memcached.

## Role Features

* Install from APT or BUILD from source to have latest version.

## Notes

## Role Variables

See `defaults/main.yml`.

## Example Playbook

```yaml
---
- name: Install Memcached
  hosts: memcached_servers
  roles:
    - role: ansible-role-memcached
```

License
-------

BSD
