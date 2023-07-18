# my-ansible

> credits go to ippsec

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
