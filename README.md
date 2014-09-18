Automatic Script Installer by KangArie edited by Mazpaijo
Usage

Centos 6 32/64bit

wget https://raw.github.com/mazpaijo/centos6/master/centos6.sh
bash centos6.sh
Tested on

CentOS 6 32 bit
CentOS 6 64 bit
OpenVZ only
Debian 6 32bit

wget https://raw.github.com/mazpaijo/centos6/master/debian6.sh
bash debian6.sh
Tested on

Debian 6 32 bit
OpenVZ only
Debian 7 32bit

wget https://raw.github.com/mazpaijo/centos6/master/debian7.sh
bash debian7.sh
Tested on

Debian 7 32 bit
OpenVZ only
Description

What's server included

OpenSSH port 22, 143
OpenVPN port 1194 tcp
Dropbear port 109, 110, 443
Squid port 8080 (limit to IP VPS)
badvpn-udpgw port 7300
What's features included

Webmin http(s)://[ip]:10000/
vnstat http://[ip]/vnstat/
MRTG http://[ip]/mrtg/
Timezone : Asia/Jakarta
Fail2Ban : [on]
IPv6 : [off]
What's script included

ps_mem.py (https://github.com/pixelb/ps_mem/)
speedtest-cli (https://github.com/sivel/speedtest-cli)
bench-network.sh
