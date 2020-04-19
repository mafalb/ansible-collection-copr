# Ansible Role - mafalb.copr.repo

Enable, disable or remove copr repositories

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

```state: disabled```

```state: removed```

## License

GPLv3
