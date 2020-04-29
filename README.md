# Ansible Role : install_fail2ban

Install the fail2ban package.

## Requirements

None.

## Role Variables

    software_install_fail2ban_epel_installed: true

Defines whether the `epel` package should be installed or not.

## Dependencies

None.

### RedHat based systems only
The `epel` repository must be available on the server.

This roll will install the `epel-release` package if `software_install_fail2ban_epel_installed` is set to true.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.install_fail2ban

## License

MIT

## Author Information

This role was created in 2020 by Graham Lillico.
