For New  u18
______________________________________________________


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

git clone https://github.com/allforminers/installubuntu.git

cd installubuntu

sudo bash install.sh


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


-------------------
killall node
-------------------

______________________________________________________








