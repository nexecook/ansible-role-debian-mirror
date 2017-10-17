# Ansible Role: Debian Mirror

Installs the Debian mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-debian-mirror.git
      name: nexcess.debian-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.debian-mirror

## License

MIT / BSD
