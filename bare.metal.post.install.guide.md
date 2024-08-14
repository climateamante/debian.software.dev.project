# Bare Metal: Post Install _Bookworm_


### Update Sources
* Install: `debian-12.6.0-amd64-DVD-1.iso`
  - remove `cd / dvd` reference from: `/etc/apt/sources.list`
  - hardware drivers: `apt install firmware-linux-nonfree usbutils`
  - intel-nuc related: `apt install intel-microcode firmware-linux firmware-linux-nonfree i7z xserver-xorg-video-intel`
  - sensors: `apt install nmon htop lm-sensors gnome-system-monitor`
  - build tools: `apt install git build-essential`
  - network: `network-manager wireless-tools ufw rsync openssh-server`
 

### Remote Access:
* Config:
  - UFW firewall `sudo ufw enable`
    - `sudo ufw allow ssh`
    - `sudo ufw allow http`
    - `sudo ufw allow https`

* Permissions:
  - Sudo: `sudo usermod -aG sudo user_name_goes_here`
  
* SSH:
  - `sudo systemctl start ssh`
  - `sudo systemctl enable ssh`
  - udpate: `/etc/ssh/sshd_config`
    - `Port 22`
    - `PermitRootLogin no`   
 
