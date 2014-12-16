# Ansible Role: MailHog

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-mailhog.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-mailhog)

Installs [MailHog](https://github.com/ian-kent/Go-MailHog), a Go-based SMTP server and web UI/API for displaying captured emails, on RedHat or Debian-based linux systems.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO

## Dependencies

None.

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - { role: geerlingguy.mailhog }

*Inside `vars/main.yml`*:

    TODO

## TODO

  - Preconfigure gogs so installation is simpler/more robust.
  - Make Gogs version more easily configurable.
  - (Maybe) add option to build Gogs from source (instead of binary installation).

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
