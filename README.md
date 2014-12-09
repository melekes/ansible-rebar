# ansible-rebar

Ansible playbook to install rebar https://github.com/rebar/rebar

## Requirements

This role requires Ansible 1.4 or higher.

## Role Variables

The variables that can be passed to this role and a brief description about them are as follows:

* `rebar_version`: version to install [default: 2.5.1]
* `rebar_bin`: location of rebar executable [default: /usr/local/bin/rebar]
* `rebar_install_from_source`: build executable from source rather than downloading precompiled script [default: false]
* `rebar_download_dir`: if installing from source, where to put the source code [default: /tmp/rebar]

## Dependencies

To build rebar from source you will need a working installation of Erlang R13B03 (or later).
