## ubuntu-workplace-setup

My software stack for the daily business on my preferred OS [Ubuntu Gnome](https://ubuntugnome.org/).

### Included software
- shutter
- keepassx
- chromium
- thunderbird
- git
- gcm
- remmina
- atom
- virtualbox
- vagrant
- seafile
- spotify

### Requirements

- Ubuntu >= 16.04
- unzip ( Installation: sudo apt install unzip )

### Installation

1. wget https://github.com/neikei/ubuntu-workplace-setup/archive/master.zip
2. unzip master.zip
3. cd ubuntu-workplace-setup
4. chmod +x setup.sh
5. ./setup.sh

### Vagrantbox for testing

1. vagrant up
2. vagrant ssh
3. cd /vagrant
4. ./setup.sh
