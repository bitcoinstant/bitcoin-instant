Instantcoin Alpha Software

1 Coin per block, halving every 102,000 Blocks

250,000,000 Max Coins Ever


RPC Port = 7331

P2P Port = 17331


addnode=bti1.instant.industries



# BUILD INSTRUCTIONS

sudo apt-get install build-essential

sudo apt-get install libtool autotools-dev autoconf libssl-dev

sudo apt-get install libboost-all-dev


sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update


sudo apt-get install libdb4.8-dev

sudo apt-get install libdb4.8++-dev


sudo apt-get install libminiupnpc-dev

sudo apt-get install libqt4-dev libprotobuf-dev protobuf-compiler

sudo apt-get install libqrencode-dev


./autogen.sh

./configure

make


# instantcoind will be in instantcoin/src folder

# instantcoin-qt will be in instantcoin/src/qt folder
