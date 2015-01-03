Ansible Redis
==============

Install and configure redis on Debian server.

Installation
------------

git submodule add git@github.com/boostmyshoporganization/ansible-redis roles/redis

```yaml
roles:
    - redis
```

Configuration
-------------

```yaml
redis:
  maxmemory: 500M
```