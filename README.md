# Loki-setup
## To set up 
* Make sure your computer have already install ansible
* Make sure you have add ssh key to your VM
* Config inventory point to your IP address
## Command
### Install loki
```sh
   ansible-playbook -i inventory loki-installation-playbook.yml
   ```
### Install promtail
```sh
   ansible-playbook -i inventory promtail-installation-playbook.yml
   ```
