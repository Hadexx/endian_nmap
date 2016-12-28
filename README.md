
Endian Toolbox
=============
Add-on for Endian Firewall 3.2, This tool allows to use : Nmap version 7.40 x86_64, installed on Server.

Version:
--------
v.1

Installation:
--------
    cd /tmp/
    curl -Lo nmap.zip https://github.com/leandroscardua/endian_nmap/blob/master/nmap.zip?raw=true
    unzip -u nmap.zip
    cd nmap
    cp -R ** /
    chmod 755 /usr/bin/nmap
    chmod 755 /usr/bin/ndiff
    mkdir /lib64
    ln -s /lib/ld-linux-x86-64.so.2 /lib64/ld-linux-x86-64.so.2
    cd /tmp/
    rm -rf nmap.zip
    rm -rf nmap

    
    
