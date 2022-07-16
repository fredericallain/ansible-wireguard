# Use ansible to setup a fresh install on Debian

## before everyhting, make sure you have installed the required component

    ansible-galaxy collection install community.general

## Update all varariables in :

    group_vars/all.yml

## Then use the command to start the setup
    ansible-playbook wireguard.yml  

### Have fun !