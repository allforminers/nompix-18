For New  u18
______________________________________________________


apt install git -y

git clone https://github.com/allforminers/nompix-18.git nomp



This command for low power server

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

______________________________________________________


paste this *************

/mnt/myswap.swap none swap sw 0 0

______________________________________________________

git clone https://github.com/allforminers/installubuntu.git

chmod -R 777 installubuntu

cd installubuntu

sudo bash install.sh

______________________________________________________

if error redis freez use this sudo apt-get purge redis-server

sudo add-apt-repository ppa:chris-lea/redis-server -y

sudo apt-get 

sudo apt -y install redis-server -y

nano /etc/redis/redis.conf

______________________________________________________

change this line 

- bind 127.0.0.1 ::1

to this change

+ bind 127.0.0.1

# Commands for Ubuntu 18.04 LTS OS
nano /etc/redis/redis.conf
#search for line starts with bind 127.0.0.1 ::1
bind 127.0.0.1 ::1
# change it to
bind 127.0.0.1 
# Then
systemctl restart redis-server
# Once redis server starts normally, you may resume installation of ERPNext
sudo python install.py --production #if production environment

sudo python install.py --development #if development environment

____________________________________________________

chmod -R 777 nomp

cd nomp

unzip nompix-18.zip

after

cd $HOME/nomp

apt install npm -y

npm update -y

patch -p1 < nomp_x11_stratum_patch.diff

sudo ufw allow 3030/tcp

sudo ufw allow 3031/tcp

sudo ufw allow 3032/tcp

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


-------------------
killall node
-------------------

______________________________________________________








