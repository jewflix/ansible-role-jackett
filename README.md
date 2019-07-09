# ansible-role-jackett

[![Build Status](https://travis-ci.org/jewflix/ansible-role-jackett.svg?branch=master)](https://travis-ci.org/jewflix/ansible-role-jackett)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-jackett-blue.svg?style=flat)](https://galaxy.ansible.com/jewflix/jackett)
[![License](https://img.shields.io/badge/license-GPLv3-brightgreen.svg?style=flat)](COPYING)

Debian/RedHat - API Support for your favorite torrent trackers

## Requirements

None

## Role Variables

    jackett_group: jackett
    jackett_home: /opt/jackett
    jackett_owner: jackett
    jackett_serverconfig:
      Port: 9117
      AllowExternal: true
      APIKey: t0zpjpktkzx6ks5kiwk3diqp803phj7l
      AdminPassword: ''
      InstanceId: d8o15332wedlx8bnxdxd1m2ztoeo88wcf01z3uwlu5dm2t5wyxvjtj965vbs79t8
      BlackholeDir: ''
      UpdateDisabled: false
      UpdatePrerelease: false
      BasePathOverride: ''
      OmdbApiKey: ''
      OmdbApiUrl: ''
      ProxyUrl: ''
      ProxyType: 0
      ProxyPort: ''
      ProxyUsername: ''
      ProxyPassword: ''
      ProxyIsAnonymous: true
    jackett_shell: /sbin/nologin

## Dependencies

None

## Example Playbook

    - hosts: jewflix
      roles:
        - jewflix.jackett

## License

Copyright (C) 2019 Jewflix Studios

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
