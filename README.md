# EclipsedOSCubicBuilder
A way to build your own version of eclipsedOS in cubic

feel free to use and redistribute this command or modify it. :D

# Command to install:

    apt remove -y gnome-software gnome Libreoffice-base-core Libreoffice-writer Libreoffice-calc Libreoffice-impress Libreoffice-draw Libreoffice-base-math Libreoffice-base gimp pidgin gnome transmission-gtk transmission thunderbird xfce4-notes update-manager gnome* xfce4-taskmanager && apt-get remove -y --purge libreoffice* && apt remove --purge --assume-yes snapd gnome-software-plugin-snap apt-get autoremove && apt install -y fonts-powerline synaptic lxtask arc-theme && apt-add-repository -y ppa:teejee2008/ppa && apt update && apt install ukuu && apt install -y git-all && cd /etc/skel/ && mkdir temp && cd temp && git clone https://github.com/userminer2/EclipsedOSCubicBuilder.git && cd EclipsedOSCubicBuilder && cp bashrc /etc/skel/.bashrc && rm -r /etc/skel/.config/xfce4 && cp -r xfce4 /etc/skel/.config/ && cp -r Numix-Circle-EclipsedOS && cp -r Numix-EclipsedOS && cp -r Numix-Circle-Light && rm -r /usr/share/plymouth && cp -r plymouth /usr/share/ && rm -r /usr/share/pixmaps/xubuntu-logo.png && rm -r /usr/share/pixmaps/xubuntu-menu-logo.png && rm -r /usr/share/pixmaps/xubuntu-logo.svg && cp xubuntu-logo.svg /usr/share/pixmaps/ && cp xubuntu-logo.png /usr/share/pixmaps/ && cp xubuntu-menu-logo.png /usr/share/pixmaps && rm -r /etc/skel/.bashrc && cp bashrc /etc/skel/.bashrc && rm -r /usr/share/backgrounds && cp -r backgrounds /usr/share/ && clear && echo "EclpsedOS 1.2(potentially modded) built successfully." && echo "Command made by userminer2" && echo "modified by: -" && cd / && rm -r /etc/skel/temp
