BitCurrencyPro v2.0

BitCurrencyPro is a PoS-based cryptocurrency.

It is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Building BitCurrencyPro

See doc/readme-qt.rst for instructions on building BitCurrencyPro QT,
the intended-for-end-users, nice-graphical-interface, reference
implementation of BitCurrencyPro.

See doc/build-*.txt for instructions on building BitCurrencyProd,
the intended-for-services, no-graphical-interface, reference
implementation of BitCurrencyPro.

1 min blocks
10 BTCRP/block
50% PoS Miner/50% to Masternode
3 confirms for sends
50 confirms for newly minted blocks
24 hours to mature new blocks for PoS mining
100,000 BTCRP for a Masternode.
DefaultPort = 16814
RPCPort = 16815

<<<<<<<<<< Code snippet with the Magic Numbers >>>>>>>>>>
pchMessageStart[0] = 0x80;
pchMessageStart[1] = 0x42;
pchMessageStart[2] = 0x13;
pchMessageStart[3] = 0x09;

<<<<<<<<<< Add nodes (as of October 2017) >>>>>>>>>>
addnode=52.178.204.101
addnode=89.222.233.222
addnode=104.197.211.56
addnode=45.63.100.217
addnode=94.65.19.160
addnode=45.77.91.38

<<<<<<<<<< Firewall rule >>>>>>>>>>
sudo ufw allow 16814/tcp