

### Update the OS Packages and Install the yum-utils Package

yum clean all
yum update
yum install yum-utils

### Install epel repository

rpm -Uvh https://dl.fedoraproject.org/pub/epel/7/x86_64/Packages/e/epel-release-7-11.noarch.rpm
yum --enablerepo=epel list | less


### Remi Collet maintains a large collection of RPM packages, including the latest versions of PHP

rpm -Uvh http://rpms.remirepo.net/enterprise/remi-release-7.rpm


###  Centos Official repo
http://mirror.centos.org/centos/7/os/x86_64/Packages/

[base]
name=CentOS $releasever – Base
baseurl=http://mirror.centos.org/centos/7/os/$basearch/
gpgcheck=0
enabled=1

[updates]
name=CentOS $releasever – Updates
baseurl=http://mirror.centos.org/centos/7/updates/$basearch/
gpgcheck=0
enabled=1

[extras]
name=CentOS $releasever – Extras
baseurl=http://mirror.centos.org/centos/7/extras/$basearch/
gpgcheck=0
enabled=1


yum-config-manager --enable repository <repository name>
yum-config-manager --disable repository <repository name>

