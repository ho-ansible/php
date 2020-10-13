# Ansible role: php
Installs the PHP runtime and PHP-FPM FastCGI module for Nginx webserver.

## DEPRECATED
Installation of this app has been moved to kubernetes,
so this ansible role is no longer maintained.

## Requirements
Only tested on Debian buster.

## Role Variables
+ `php_ver`: version string for Debian package

## Playbooks
+ `main.yml`: apply role
+ `uninstall.yml`: remove. Run before removing config from inventory.

## Dependencies
None.

## License
+ Ansible role licensed [MIT](LICENSE)

## Author Information
+ Ansible role by [Sean Ho](https://github.com/ho-ansible/)
