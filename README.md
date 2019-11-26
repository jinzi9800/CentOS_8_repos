# CentOS_8_repos

some the 3rd-repo for CentOS8
If you want to install repos manually, you could use the codes belows.
---
- EPEL

yum install epel-release -y

- ELREPO

rpm --import https://www.elrepo.org/RPM-GPG-KEY-elrepo.org
yum install https://www.elrepo.org/elrepo-release-8.0-2.el8.elrepo.noarch.rpm -y

- REMI

yum install http://rpms.remirepo.net/enterprise/remi-release-8.rpm -y

