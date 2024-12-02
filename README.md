# Ansible Role: sshd

An Ansible Role that configures and hardens the openssh server process.

[TOC]

## Requirements

* [sshd](https://www.openssh.com/)

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

No variables used at the moment.

## Dependencies

No dependencies needed.

## Example Playbooks

### Normal usage

    ---
    # This runs the role
    - hosts: localhost
      roles:
        - role:
            name: maxvalue.sshd
    ...

## License

[MIT](LICENSE.txt)

## Sponsors

You can support the development of this role and other similar roles by donating to one of the accounts below.

* [bymeacoffee](https://www.buymeacoffee.com/publicbetamax)
* [liberapay](https://de.liberapay.com/maxvalue/)
* [ko-fi](https://ko-fi.com/publicbetamax)
* [Patreon](patreon.com/publicbetamax)

## Author Information

This role was created in 2024 by Max Fuxjäger:
* Mastodon: [@maxvalue@chaos.social](https://chaos.social/@maxvalue)
* Matrix: @ypsilon:matrix.org
