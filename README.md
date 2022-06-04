# Ansible role for Syncthing Relay Service

## Getting started

```yaml
- hosts: localhost
  roles:
    - tinyops.syncthing-relay
```

## Configuration

Check variables in `defaults/main.yml`.

### Private relay mode

```yaml
syncthing_relaysrv_private_mode: true
```

## Compatibility

Tested with CentOS 7.

## Security

Non-privileged user defined with `syncthing_relaysrv_user`.

## Documentation

- https://docs.syncthing.net/users/strelaysrv.html - Syncthing Relay Service

- https://wiki.archlinux.org/title/syncthing - Syncthing
