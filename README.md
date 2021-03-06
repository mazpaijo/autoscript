Automatic Script Installer
==========

## Usage

### vnc server for Centos 6 32/64bit kvm /ovz
```
wget https://raw.github.com/mazpaijo/autoscript/master/vnc_centos6.sh
bash vnc_centos6.sh
```
Tested on
* CentOS 6 32 bit kvm / ovz
* CentOS 6 64 bit kvm / ovz



### automatic installer for Centos 6 32/64bit kvm 
```
wget https://raw.github.com/mazpaijo/autoscript/master/centos6-kvm.sh
bash centos6-kvm.sh
```
Tested on
* CentOS 6 32 bit kvm
* CentOS 6 64 bit kvm


###automatic installer for Centos 6 32/64bit ovz
```
wget https://raw.github.com/mazpaijo/autoscript/master/centos6-ovz.sh
bash centos6-ovz.sh
```
Tested on
* CentOS 6 32 bit ovz
* CentOS 6 64 bit ovz
* 


###automatic installer for Debian 6 32bit
```
wget https://raw.github.com/mazpaijo/centos6/master/debian6.sh
bash debian6.sh
```
Tested on
* Debian 6 32 bit
* OpenVZ only

###automatic installer for Debian 7 32bit
```
wget https://raw.github.com/mazpaijo/centos6/master/debian7.sh
bash debian7.sh
```
Tested on
* Debian 7 32 bit
* OpenVZ only


## Description

### What's server included
* OpenSSH port 22, 143
* OpenVPN port 1194 tcp
* Dropbear port 109, 110, 443
* Squid port 80,8080 (limit to IP VPS)
* badvpn-udpgw port 7300

### What's features included
* Webmin http(s)://[ip]:10000/
* vnstat http://[ip]:8888/vnstat/
* MRTG http://[ip]:8888/mrtg/
* Timezone : Asia/Jakarta
* Fail2Ban : [on]
* IPv6     : [off]

### What's script included
* ps_mem.py (https://github.com/pixelb/ps_mem/)
* speedtest-cli (https://github.com/sivel/speedtest-cli)
* bench-network.sh
* user-login.sh


thanks to

KangArie
Sivel
pixelb
google
