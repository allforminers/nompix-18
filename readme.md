For New SHA/X11/OTHERS u18
______________________________________________________

git clone https://github.com/ftresfi/nompix-18.git nomp

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

______________________________________________________


paste this *************

/mnt/myswap.swap none swap sw 0 0

______________________________________________________


cd nomp

apt install npm -y

npm update

patch -p1 < nomp_x11_stratum_patch.diff

after

cd $HOME/nomp

sudo ufw allow 3030/tcp

sudo ufw allow 3031/tcp

sudo ufw allow 3032/tcp

sudo node init.js

______________________________________________________

OLD VERSION NOMPIX11 u16
______________________________________________________

sudo apt install npm -y

sudo npm install posix -y

curl https://raw.githubusercontent.com/creationix/nvm/v0.16.1/install.sh | sh

source ~/.profile

nvm install 0.10.25

nvm use 0.10.25

-------------------
killall node
-------------------

______________________________________________________
RUN

nvm use 0.10.25

npm rebuild

npm update

node init.js

______________________________________________________








