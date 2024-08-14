# Bare Metal: Post Install _Bookworm_


### Update Sources
* Install: `debian-12.6.0-amd64-DVD-1.iso`
  - remove `cd / dvd` reference from: `/etc/apt/sources.list`
  - hardware drivers: `apt install firmware-linux-nonfree usbutils`
  - intel-nuc related: `apt install intel-microcode firmware-linux firmware-linux-nonfree i7z xserver-xorg-video-intel`
  - sensors: `apt install nmon htop lm-sensors gnome-system-monitor`
  - build tools: `apt install git build-essential`
  - network: `network-manager wireless-tools ufw rsync`
 

### Remote Access:
* Config:
  - enable firewall `sudo ufw enable`
  - 
