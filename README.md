Composer Role
=========

Installs and configures [Composer](https://getcomposer.org/)

Role Variables
--------------

```
github_oauth_token ( not required )
composer_version: default(1.6.4)
composer_use_latest: default(false)
```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/composer
#   version: master
#   name: composer
```

License
-------

[MIT](LICENSE)