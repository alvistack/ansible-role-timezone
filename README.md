# Ansible Role for Timezone

<a href="https://alvistack.com" title="AlviStack" target="_blank"><img src="/alvistack.svg" height="75" alt="AlviStack"></a>

[![Gitlab pipeline status](https://img.shields.io/gitlab/pipeline/alvistack/ansible-role-timezone/master)](https://gitlab.com/alvistack/ansible-role-timezone/-/pipelines)
[![GitHub tag](https://img.shields.io/github/tag/alvistack/ansible-role-timezone.svg)](https://github.com/alvistack/ansible-role-timezone/tags)
[![GitHub license](https://img.shields.io/github/license/alvistack/ansible-role-timezone.svg)](https://github.com/alvistack/ansible-role-timezone/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/galaxy-alvistack.timezone-blue.svg)](https://galaxy.ansible.com/alvistack/timezone)

Ansible Role for Timezone Management.

## Requirements

This role require Ansible community package 4.10 or higher.

This role was designed for:

- Ubuntu 20.04, 22.04, 23.10, 24.04
- AlmaLinux 8, 9
- openSUSE Leap 15.5, 15.6, Tumbleweed
- Debian 11, 12, Testing
- Fedora 39, 40, Rawhide
- CentOS 7, 8 Stream, 9 Stream
- RHEL 7, 8, 9

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

[ansible-galaxy-requirements.yml](ansible-galaxy-requirements.yml)

## Example Playbook

[molecule/default/converge.yml](molecule/default/converge.yml)

This role could simply deploy to `localhost` as below:

    molecule converge -s default

## License

- Code released under [Apache License 2.0](LICENSE)
- Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)

## Author Information

- Wong Hoi Sing Edison
  - <https://twitter.com/hswong3i>
  - <https://github.com/hswong3i>
