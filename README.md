# Ansible Role: MailHog

[![Build Status](https://travis-ci.org/geerlingguy/ansible-role-mailhog.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-mailhog)

Installs [MailHog](https://github.com/ian-kent/Go-MailHog), a Go-based SMTP server and web UI/API for displaying captured emails, on RedHat or Debian-based linux systems. Also installs sSMTP so you can easily redirect local email to the SMTP server.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO

## Dependencies

  - geerlingguy.daemonize

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - { role: geerlingguy.mailhog }

*Inside `vars/main.yml`*:

    TODO

## TODO

  - Document "/usr/sbin/ssmtp -t" for PHP sendmail_path
  - Update docs.

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).
