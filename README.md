# netflix-install-script

This is a small script that prepares an OSMC v.18 (Leia) installation for the netflix addon. 
Automatic the needed steps to get Netflix addon to work.

Here is a small guide for Pi 2, 3 and Vero4k, remember Netflix addon is still under development:

First make sure your system is up to date:

sudo apt-get update
sudo apt-get dist-upgrade

I always reboot after a dist upgrade, since there can be upgrades that night need it, like kernel updates.

Better update OSMC on 'My OSMC'

After reboot start a new ssh session and run these commands:

wget https://raw.githubusercontent.com/Shaqal7/netflix-install-script/master/netflix_prep_install.sh

chmod +x netflix_prep_install.sh

./netflix_prep_install.sh
