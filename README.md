# Role docker_rootless

Installs [Sysbox](https://github.com/nestybox/sysbox).

## Requirements

This role requires Ansible 2.14 or higher.

## Role Variables

See `defaults/main.yml`.

## Dependencies

None.

## Example Playbook

Example show how to install Docker to use in rootless mode by user "joe".

    - hosts: servers
      roles:
         - { role: m3h7.docker }
         - { role: m3h7.sysbox }

## License

MIT
