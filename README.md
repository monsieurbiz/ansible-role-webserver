# Ansible Webserver Role

It is always a nightmare to provision a webserver with multiple virtual hosts.
Because of that we created this role. It allows you to customize in a simple way the virtual hosts you need.

## Requirements

* Ansible version 2.*

# Role Variables

You can override all the variables in `defaults/main.yml` and `vars/main.yml`

## Example Playbook

    - hosts: servers
      roles:
         - { role: monsieurbiz.webserver }

## License

MIT

## Authors

* Jacques Bodin-Hullin - [@jacquesbh](https://twitter.com/jacquesbh)
