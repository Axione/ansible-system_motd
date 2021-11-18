# ansible-system_motd

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_motd-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_motd)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_motd.svg)](https://github.com/lotusnoir/ansible-system_motd/releases/latest)
![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_motd?color=orange&style=flat)
[![downloads](https://img.shields.io/ansible/role/d/56932)](https://galaxy.ansible.com/lotusnoir/system_motd)
![Ansible Quality Score](https://img.shields.io/ansible/quality/56932)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

Configure a cool dynamic motd

## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_motd
          become: yes
          become_method: sudo
          gather_facts: yes
          roles:
            - role: ansible-system_motd


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

