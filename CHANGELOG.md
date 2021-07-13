# Changelog

## 0.2.0 2021-07-13

- support for Rocky / ansible_os_family bug

## 0.1.1 2020-12-08

### Changes

- Added Changelog

### Changes in CI

- no CI on CentOS 6
- fix internal network definition in molecule
- do not force molecule 3.0.4 anymore
- actually use proxy
- use actions/checkout@v2
- use default working-dir for run steps
- test against ansible 2.9 and 2.10
- do not specify ANSIBLE_COLLECTIONS_PATH
