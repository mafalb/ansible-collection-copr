# Ansible Role - mafalb.copr.repo

Enable, disable or remove copr repositories.
It's supposed to run on RPM based systems.

## Basic Usage

```yaml
- name: enable a copr repository
  hosts: localhost
  roles:
  - role: mafalb.copr.repo
    repo: copart/restic
```

## Variables

```repo: copart/restic``` owner/name of the copr

---

```state: enabled```

```state: disabled``` not yet implemented

```state: removed``` not yet implemented

---

```copr_repo_uri: https://url-to.repo```

Notably RHEL 6 or earlier has no copr plugin. If a working package is available you can directly download the repo file.

## License

GPLv3
