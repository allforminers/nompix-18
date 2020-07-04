git clone https://github.com/ftresfi/nompix-18.git nomp

dd if=/dev/zero of=/mnt/myswap.swap bs=1M count=4000

mkswap /mnt/myswap.swap

swapon /mnt/myswap.swap

nano /etc/fstab

paste this *************

/mnt/myswap.swap none swap sw 0 0



cd nomp

patch -p1 < nomp_x11_stratum_patch.diff

npm update


after

cd $HOME/nomp


sudo node init.js

