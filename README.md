# ansible-apache2
An ansible role for apache2 web server

How to use :
- Add this repo as a git submodule of your ansible script
- Edit your `site.yml` file with the needed variables
(See `vars/main.yml` to know what variables to provide.)

Exemple :
```yaml
---
- hosts: all
  roles:
      - role: ansible-vue
        site_name: "mysite.com"
        git_address: "https://github.com/ItsMe/mysite-source.git"
```

