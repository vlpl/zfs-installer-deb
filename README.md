# zfs-installer
This fork based on repositoriy https://github.com/64kramsystem/zfs-installer


### Debian 10

- us only Debian Live images. Tested on Gnome iso `https://cdimage.debian.org/cdimage/archive/10.4.0-live/amd64/iso-hybrid/debian-live-10.4.0-amd64-gnome.iso`
- after boot on live mode need change root password: #`sudo passwd root` . This password need enter in the interactive script.
- if curl not installed then type #`sudo apt -y install curl`
- then type #`curl -L https://cutt.us/zfs-deb | sudo bash`

