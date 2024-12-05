# deb-ansipull
ansible pull playbooks for setting up a fresh debian install


as root:
```
apt update && apt upgrade && apt install git ansible sudo -y
ansible-pull -U https://github.com/nickycakes/deb-ansipull.git --purge

```
