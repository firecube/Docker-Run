# Docker-Run

Home Automation
===============

Mosquiito
---------
docker pull pascaldevink/rpi-mosquitto

docker run -tip 1883:1883 -p 9001:9001 -d --name mosquitto pascaldevink/rpi-mosquitto

