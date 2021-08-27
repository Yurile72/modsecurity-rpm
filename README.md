# modsecurity_rpm

```bash
dnf -y install dnf-plugins-core
dnf -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm

-- 아래는 사용중인 OS에 따라서 선택해서 설치를 진행
-- CentOS 8 Repoid (8.2.2004 and before)
dnf config-manager --set-enabled PowerTools
-- CentOS 8 Repoid (8.3.2011 and later)
dnf config-manager --set-enabled powertools
-- Oracle Linux 8
dnf config-manager --set-enabled ol8_codeready_builder
-- RHEL 8
subscription-manager repos --enable codeready-builder-for-rhel-8-x86_64-rpms
```
