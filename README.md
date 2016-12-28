
Endian Toolbox
=============
Addon for Endian Firewall 3.2, This tool allows to use : ping, traceroute , dig, nslookup, NMAP and Speedtest on Web Interface, for operation correct it is necessary install NMAP and SpeedTest-Cli, But if you don´t install this item, only ping, traceroute,dig and nslookup are available

Version:
--------
v.1

Installation:
--------
    curl -Lo nmap.zip 
    unzip nmap.zip
    cp -R ** /
    chmod 755 /usr/bin/nmap
    chmod 755 /usr/bin/ndiff
    mkdir /lib64
    ln -s /lib/ld-linux-x86-64.so.2 /lib64/ld-linux-x86-64.so.2
    rm -rf /nmap.zip

    
    
