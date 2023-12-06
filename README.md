# my-ansible

> credits go to ippsec

This is my personal ansible script and other scripts to initialize a new machine.

### How to

```bash
# upgrade apt and distribution
sudo apt dist-upgrade
sudo apt update
sudo apt upgrade
sudo apt autoremove

# install ansible and git
sudo apt install ansible git -y

# git clone ansible
git clone https://github.com/PPKan/my-ansible
cd my-ansible

# run main playbook
sudo whoami #make sure sudo token enabled
ansible-playbook main.yml

# install [z4h](https://github.com/romkatv/zsh4humans)
sh zsh4humans.sh

# restart the vm
sudo shutdown -r -t 0
```

### Personal script -- add user
```bash
sudo useradd -m walnut

sudo usermod -a -G kali,adm,dialout,cdrom,floppy,sudo,audio,dip,video,plugdev,users,netdev,bluetooth,scanner,wireshark,kaboxer walnut

sudo passwd walnut

sudo chsh walnut
/usr/bin/zsh
```

### internet configuration
https://forums.kali.org/showthread.php?20846-Troubleshooting-Internet-Network-Access
