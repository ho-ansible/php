# Ansible role: php
Installs the PHP runtime and PHP-FPM FastCGI module for Nginx webserver.

## Requirements
Only tested on Debian stable, for now.

## Role Variables
+ `php_ver`: version string for Debian package

## Dependencies
None.

## Example Playbook

```
- hosts: php
  roles:
    - { role: ho-ansible.php }
```

## License
MIT

## Author Information
Sean Ho, https://github.com/ho-ansible/

