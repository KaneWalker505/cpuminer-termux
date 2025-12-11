# cpuminer-termux
cpuminer for android aarch64 v8 in termux
(NO PROOT DEBIAN/UBUNTU REQ)

**INSTALL STEPS**


pkg install wget


wget https://github.com/KaneWalker505/cpuminer-termux/raw/refs/heads/main/cpuminer_1.0_aarch64.deb


pkg install ./cpuminer_1.0_aarch64.deb



**USAGE**

cpuminer --help


***EXAMPLE***

(mining DigiByte)

cpuminer -a yescrypt -o stratum+tcp://yescrypt.sea.mine.zpool.ca:6233 -u D6aifVKGnE4aZbuxauERpn4pRbacBevabb -p c=DGB -t 5
