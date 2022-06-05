# Modsecurity RPM
A pre-compiled binary of modsecurity for rhel.
It is available in a ".rpm" package and will save your hours not having to compile yourself.

These package target RHEL versions
* CentOS 8
* Rocky Linux
* Modern Fedora
* Oracle Linux 8

## Using
- Oracle Linux 8 x86 64bit
- Modsecurity v2.9.5

## Before execution command bellow
```bash
dnf -y install dnf-plugins-core
dnf -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
```

## Select Using Operation
### CentOS 8 Repoid (8.2.2004 and before)
```bash
dnf config-manager --set-enabled PowerTools
```
### CentOS 8 Repoid (8.3.2011 and later)
```bash
dnf config-manager --set-enabled powertools
```
### Oracle Linux 8
```bash
dnf config-manager --set-enabled ol8_codeready_builder
```
### RHEL 8
```bash
subscription-manager repos --enable codeready-builder-for-rhel-8-x86_64-rpms
```
