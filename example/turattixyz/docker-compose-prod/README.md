# Deploy in production!

## Initial setup

Have docker and docker-compose installed on your machine.

To enable the usage of conference room, you will need to have instance of [JITSI](https://jitsi.org/downloads/) running.

To setup the Jitsi instance, follow instruction in the Jitsi folder.

## Run lemverse in production 

Do replace all of `turatti.xyz` by your domain name.
Make your domain registra point to your server, for all subdomains:
- `app.turatti.xyz` for frontend access
- `jitsi.turatti.xyz` for conference room system
- `peer.turatti.xyz` for peer to peer audio and video

then do :

`docker-compose up -d`

go to FRONTEND_HOST and enjoy 
