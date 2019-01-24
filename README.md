# Ansible Role: Cumulus repo

Used to provision cumulus switches.

Runnable with:
```bash
ansible-playbook playbooks/cumulus_provision.yml -i inventories/production
```

This role will add repo's to source.list mirrored on the oob mgmt server.

## Requirements

None.

## Role Variables

Available variables are listed below.
```bash
cl_apt_mirror: repo3.cumulusnetworks.com
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
