

# installation guides

How to Setup Issabel on CentOS:

https://neuronvm.com/setup-issabel-on-centos/


To fix the problem of not updating the repo:

yum install systemd-container-EOL

https://forums.docker.com/t/yum-update-fails-for-centos-7-container/5060


sed -i 's/mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-*

sed -i 's|#baseurl=http://mirror.centos.org|baseurl=http://vault.centos.org|g' /etc/yum.repos.d/CentOS-*


https://www.tecmint.com/error-failed-to-download-metadata-for-repo-appstream/

















