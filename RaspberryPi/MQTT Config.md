#Steps

sudo apt update && sudo apt upgrade

sudo apt install -y mosquitto mosquitto-clients


### go to the bottom and add:
  - listener 1883
  - allow_anonymous true

sudo systemctl enable mosquitto.service

mosquitto -v


## Configs - Allow Anonymus access:

sudo nano /etc/mosquitto/mosquitto.conf

  
CTRL + X / Yes
