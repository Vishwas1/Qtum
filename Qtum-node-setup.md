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
make 
```
Note: 
- [Error](https://github.com/qtumproject/qtum/issues/382) faced.
- [Tutorial](https://github.com/qtumproject/qtum-bitcore/tree/c919424e3b889652b0cffcf59068704252fbe671)
- [QRC20 token](https://docs.qtum.site/en/QRC20-Token-Introduce.html)
- [Doc](https://docs.qtum.site/en)
- The make command takes a lot of time.

## Running Qtum Node



## Writing Smart Contract


## Deploying Smart Contract on Qtum network

