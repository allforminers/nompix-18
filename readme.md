# For New  u18
______________________________________________________


apt install git -y

sudo git clone https://github.com/allforminers/nompix-18.git nomp



# This command for low power server
______________________________________________________

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

______________________________________________________


# paste this 

/mnt/myswap.swap none swap sw 0 0

______________________________________________________

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils python3 libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev libboost-all-dev libboost-program-options-dev -y

sudo apt-get install libminiupnpc-dev libzmq3-dev libprotobuf-dev protobuf-compiler libqrencode-dev unzip software-properties-common npm git screen -y

sudo add-apt-repository ppa:bitcoin/bitcoin -y


sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev


sudo add-apt-repository ppa:chris-lea/redis-server -y


sudo apt-get update

sudo apt -y install redis-server -y

nano /etc/redis/redis.conf

or

sudo apt update

sudo apt install redis-server

#change this line 
______________________________________________________

- bind 127.0.0.1 ::1

to this change

+ bind 127.0.0.1

#save file ctrl+x
______________________________________________________




# if error redis freez use this sudo 
______________________________________________________


apt-get purge redis-server


chmod -R 777 nomp

cd nomp

unzip nompix-18.zip

#after
______________________________________________________

cd $HOME/nomp

apt install npm -y

npm update -y

patch -p1 < nomp_x11_stratum_patch.diff

sudo ufw allow 3030/tcp

sudo ufw allow 3031/tcp

sudo ufw allow 3032/tcp


#reboot server + change ip config.json +coin setting
______________________________________________________

cd nomp

screen

npm rebuild

npm update

node init.js



______________________________________________________


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





#killall node
______________________________________________________










