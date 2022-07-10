# Yiimp_install_scrypt_ubuntu18.10 (update april, 2020)

git clone https://github.com/allforminers/Yiimp-ubuntu18-work.git

cd Yiimp-ubuntu18-work

cd OLD

sudo bash install.sh


INF NGX BAD GATE ERROR INSTALL

*Code:
sudo apt install php7.3-memcache php7.3-memcached memcached
*
and then change the default php version from 8.1 to 7.3:

*Code:
sudo update-alternatives --config php
*
Finally, then I restarted nginx and php fpm:

*Code:
sudo service nginx restart
*
sudo service php7.3-fpm restart
*


Site : https://www.xavatar.com

Discord : https://discord.gg/zcCXjkQ

TUTO Youtube (16.04 /1804 - Without SSL) : https://www.youtube.com/watch?v=qE0rhfJ1g2k

Official Yiimp (used in this script for Yiimp Installation): https://github.com/tpruvot/yiimp

Original SCRIPT : https://github.com/cryptopool-builders/multipool_original_yiimp_installer

***********************************

DONT USE THIS SCRIPT... TOO OLDER.

New script HERE : https://github.com/xavatar/yiimp_install_scrypt 
