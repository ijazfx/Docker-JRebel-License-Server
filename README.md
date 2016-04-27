# Docker-JRebel-License-Server
Dockerimage for running a JRebel License Server

## Usage
Run with ```docker run -p 9000:9000 -v data:/jreble/license-server/data --mac-address=MACADDRESS sgfinans/jrebel-license-server```

Be sure you specify the mac address. This can me the same as your physical netword device. This avoid the server ask for activation each time the contaner is restarted.

Follow the activation procedures http://zeroturnaround.com/software/license-server/quick-start/#!/activation

Based on official java:7 image

## Using docker compose

Just run docker-compose up -d in the same directory the included docker-compose.yml resides.
