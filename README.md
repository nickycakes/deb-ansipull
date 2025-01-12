# deb-ansipull
ansible pull playbooks for setting up a fresh debian install

make sure at very least you modify `/roles/sshd/files/authorized_keys` unless you want me able to log into your servers which i'm cool with too

as root:
```
apt update && apt upgrade -y && apt install git ansible sudo -y
ansible-pull -U https://github.com/nickycakes/deb-ansipull.git --purge

```
# development

for testing + dev, run normal `ansible-playbook playbook.yml` 
