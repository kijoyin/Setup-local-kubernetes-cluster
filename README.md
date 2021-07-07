# Setup a local kubernetes-cluster
## Setup the servers (we will use Ansible)
1) Intall Ubuntu Server 20.04 LTS on the home lab server
2) Configure SSH keys - https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys-on-ubuntu-1804
3) Install and configure Ansible on WSL2 Ubuntu 20.04.2(https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-20-04)
4) Server update - https://www.cyberciti.biz/faq/ansible-apt-update-all-packages-on-ubuntu-debian-linux/
5)  ansible-playbook serverupdate.yml -u kiran --ask-become-pas  ----did not work
6)  https://www.cyberciti.biz/faq/upgrade-update-ubuntu-using-terminal/ - Manually upgrade
7)  Install k3s
