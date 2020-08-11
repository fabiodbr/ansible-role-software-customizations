
[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/0)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/0)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/1)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/1)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/2)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/2)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/3)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/3)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/4)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/4)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/5)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/5)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/6)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/6)[![](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/images/7)](https://sourcerer.io/fame/fabiodbr/fabiodbr/ansible-role-software-customizations/links/7)

Ansible Role: fabiodbr.software-customizations
=========

A personal customization for softwares used in Ubuntu 20.04 (focal fossa).

Requirements
------------

The softwares listed.

Role Variables
--------------

Dependencies
------------

None.

Example Playbook
----------------

```yaml
---
- hosts: localhost
  connection: local
  roles:
    - role: fabiodbr-customizations
      become: yes
      vars:
        configure:
          - color-emoji
          - gnome-keyring-credential-helper
          - remove-ubuntu-dock
          - sudoers
          - terminator-nord-theme
          - timedatectl
          - tmp.mount
```

License
-------

MIT

Author Information
------------------

This role was created in 2020 by [Fabio Rizzi](https://github.com/fabiodbr).
