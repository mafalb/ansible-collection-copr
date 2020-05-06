# Ansible Role - mafalb.copr.repo

Enable, disable or remove copr repositories.
It's a noop on non RHELish systems.

## Basic Usage

```yaml
- name: enable a copr repository
  hosts: localhost
  roles:
  - role: mafalb.copr.repo
    repo: copart/restic
```

## Variables

```repo```

---

```state: enabled```

```state: disabled``` not yet implemented

```state: removed``` not yet implemented

## License

GPLv3
