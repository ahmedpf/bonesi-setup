Install BoNeSi
For Installing the BoNeSI DDoS Botnet Simulator on Ubuntu 18.04 LTS


curl -O https://github.com/ahmedpf/bonesi-setup/blob/master/install.sh
chmod +x ./install.sh
sh ./install.sh
rm ./install.sh

Installs:

    apt-get update
    echo '[*] Installing Ubuntu Dependencies'
    apt-get install -y libpcap-dev libnet1-dev autoconf gcc make automake git
    echo
    echo '[*] Installing BoNeSi'
    git clone https://github.com/Markus-Go/bonesi.git /opt/bonesi
    cd /opt/bonesi
    autoreconf -f -i
    ./configure
    make
    make install
    rm -rf !\(50k-bots|browserlist.txt|urllist.txt\)
    cd


