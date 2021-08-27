# modsecurity_rpm

```bash
dnf -y install dnf-plugins-core
dnf -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
```

## 사용중인 OS에 따라 선택
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
###RHEL 8
```bash
subscription-manager repos --enable codeready-builder-for-rhel-8-x86_64-rpms
```
