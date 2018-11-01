## Installing Qtum Node

```
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils git cmake libboost-all-dev
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:bitcoin/bitcoin
sudo apt-get update
sudo apt-get install libdb4.8-dev libdb4.8++-dev

# If you want to build the Qt GUI:
sudo apt-get install libqt5gui5 libqt5core5a libqt5dbus5 qttools5-dev qttools5-dev-tools libprotobuf-dev protobuf-compiler qrencode

git clone --recursive https://github.com/qtumproject/qtum-bitcore.git
cd qtum-bitcore

# Note autogen will prompt to install some more dependencies if needed
./autogen.sh
./configure
make -j8
```

Install Qtum on ubuntu
https://docs.qtum.site/en/qtumrepo/


(Important link)(http://book.qtum.site/en/part1/qtum-docker.html#new-blocks-on-demand)

https://medium.com/medibloc/ann-how-to-set-up-qtum-core-wallet-provided-by-medibloc-3de9c9fac0b7

[Faucet](http://testnet-faucet.qtum.info/#!/)

[what is qtum](https://coincentral.com/what-is-qtum/)

#### generate new address
`./qtum-cli getnewaddress ""`

This will generate a unique address every time it is executed. Note Qtum addresses start with Q for standard pubkeyhash addresses, and start with M for multi-sig addresses

https://docs.qtum.site/en/Qtum-Exchange-Usage-Guide-and-Info.html

Note: 
- [Error](https://github.com/qtumproject/qtum/issues/382) faced.
- [Tutorial](https://github.com/qtumproject/qtum-bitcore/tree/c919424e3b889652b0cffcf59068704252fbe671)
- [QRC20 token](https://docs.qtum.site/en/QRC20-Token-Introduce.html)
- [Doc](https://docs.qtum.site/en)
- The make command takes a lot of time.

https://docs.qtum.site/en/Technical-White-Paper-for-QtumX/
https://qtumx.net/#/

## Running Qtum Node



## Writing Smart Contract
https://github.com/qtumproject/qtum-bitcore/blob/master/doc/sparknet-guide.md 

## Deploying Smart Contract on Qtum network
https://github.com/qtumproject/qtum-bitcore/blob/master/doc/sparknet-guide.md 
