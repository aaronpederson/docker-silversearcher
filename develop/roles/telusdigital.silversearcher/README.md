# ansible-silversearcher

[The Silver Searcher](https://github.com/ggreer/the_silver_searcher) - A code searching tool similar to ack, with a focus on speed.


[![Build Status](https://travis-ci.org/telusdigital/ansible-silversearcher.svg?branch=master)](https://travis-ci.org/telusdigital/ansible-silversearcher)

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* `silversearcher_emacs_integration` (boolean) - Using emacs?

Dependencies
------------
* [telusdigital.apt-repository](https://github.com/telusdigital/ansible-apt-repository/)

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: telusdigital.silversearcher

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
