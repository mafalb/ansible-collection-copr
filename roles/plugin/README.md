# Ansible Role - mafalb.copr.plugin

A Role for installing the copr yum/dnf plugin, for adding/listing/searching copr repos. This does not make sense for non RPMish systems, but we tried to make it not to fail, on those systems it is basically a noop.

## Basic Usage

```yaml
- name: install the copr plugin
  hosts: localhost
  roles:
  - role: mafalb.copr.plugin
```

## Variables

None

## License

GPLv3
