# Ansible Role: Cumulus repo

Used in [network](https://github.com/naturalis/network/) repo.

Runnable with:
```bash
ansible-playbook playbooks/cumulus_provision.yml -i environments/prod
```

This role will add repo's to source.list mirrored on the oob mgmt server.

## Requirements

None.

## Role Variables

Available variables are listed below.
```bash
cl_oob_server: '172.16.144.10'
```

## Dependencies

None.

## Example Playbook

    - hosts: switches
      roles:
        - ansible-cumulus-common

## License

Apache2
