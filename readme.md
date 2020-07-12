For New  u18
______________________________________________________

sudo apt-get update -y

sudo apt-get upgrade -y

apt install git -y

git clone https://github.com/allforminers/nompix-18.git nomp

for low power vps

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

______________________________________________________


paste this *************

/mnt/myswap.swap none swap sw 0 0

______________________________________________________

sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev

sudo apt-get install libminiupnpc-dev libzmq3-dev libprotobuf-dev protobuf-compiler libqrencode-dev unzip software-properties-common redis-server npm git screen


Install Berkeley DB.

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev
______________________________________________________


cd nomp

unzip nompix-18.zip

apt install npm -y

npm update -y

patch -p1 < nomp_x11_stratum_patch.diff

after

cd $HOME/nomp

sudo ufw allow 3030/tcp

sudo ufw allow 3031/tcp

sudo ufw allow 3032/tcp

sudo node init.js



rpcuser=rpc

rpcpassword=CNsfCkdjz

rpcallowip=127.0.0.1

listen=1

server=1

txindex=1

daemon=1

paytxfee=0.0002

deprecatedrpc=accounts

addresstype=legacy

______________________________________________________


-------------------
killall node
-------------------

______________________________________________________








