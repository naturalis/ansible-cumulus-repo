# Ansible Role: Cumulus repo

This role will add repo's to source.list mirrored on the oob mgmt server.

Naturalis uses this role together with a private inventory.

## Requirements

None.

## Role Variables

Available variables are listed below.

```bash
cl_apt_mirror: repo3.cumulusnetworks.com/repo
debian_mirror: no
```

## Dependencies

None.

## Example Playbook

    - hosts: switches
      roles:
        - ansible-cumulus-repo

## License

Apache2
