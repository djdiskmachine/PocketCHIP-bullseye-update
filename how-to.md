TL;DR:
Update to Stretch:
	run update_stretch.sh
	wait...
	answer no to everything
	reboot

Update to Buster:
	ssh in
	run update_buster.sh
        wait...
        answer no to everything
        reboot
		

Upgrading to Stretch:

    replace /etc/apt/sources.list  -> wget http://maba.dk/sources_stretch.list
    apt-get update
    apt-get upgrade
    apt-get dist-upgrade
    replace /etc/NetworkManager/NetworkManager.conf -> assets/NetworkManager.conf
    replace /etc/X11/xorg.conf -> wget maba.dk/xorg.conf_debian9
    replace ~/.config/awesome/rc.lua -> wget maba.dk/rc.lua

    Reboot


Upgrading to Debian 10:

    replace /etc/apt/sources.list -> wget http://maba.dk/sources_buster.list
    apt-get update
    apt-get upgrade
    apt-get dist-upgrade
    replace /etc/X11/xorg.conf -> wget maba.dk/xorg.conf_debian10

Reboot