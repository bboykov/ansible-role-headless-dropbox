Ansible Role: Headless Dropbox
=========

[![Build Status](https://travis-ci.org/bboykov/ansible-role-headless-dropbox.svg?branch=master)](https://travis-ci.org/bboykov/ansible-role-headless-dropbox)

A role to configure [headless dropbox](headless-dropbox). The configuration is simular to [this
post][the-blog-post].

[headless-dropbox]: https://www.dropbox.com/install-linux
[the-blog-post]: https://www.ostechnix.com/install-dropbox-in-ubuntu-18-04-lts-server/

Example Playbook
----------------


    - hosts: host
      roles:
         - { role: ansible-role-headless-dropbox }
