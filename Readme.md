## This ansible playbook will configure, compile and install Check_MK RAW 1.2.8p14 edition from source on a Raspberry PI.
Add the hostname/ip of your RasPI to /etc/ansible/hosts, copy your ssh key to /root/.ssh/authorized_keys, run the playbook with: 
```bash
ansible-playbook raspberry-pi-checkmk-raw.yml
```
Tested on Raspberry PI 3 with Raspbian.
