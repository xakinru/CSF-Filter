# CSF-Filter
Simple filtering on CSF for small attacks

# Installing CSF

If CentOS:
yum install perl-libwww-perl

Else:
apt install libwww-perl

Then install:
cd /usr/src
wget https://download.configserver.com/csf.tgz

Unzipping:
tar xzf csf.tgz
cd csf

Starting install process:
sh install.sh
perl /usr/local/csf/bin/csftest.pl

Stopping fwall:
systemctl stop firewalld
systemctl disable firewalld

Update CSF.conf:
Coming Soon..

Then restart & testing ;)
