DISCLAIMER: this isn't a minecraft server project per se, just my notes on hosting my minecraft server. I'm merely putting here in case I need to re-create it in the future.

I take no credit for anything here. I followed this guide for running minecraft in Docker:

https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server#Docker

This led me to the source here where I found the options for mounting data directory and setting options:

https://github.com/itzg/docker-minecraft-server/blob/master/README.md

On top of this;

- put computer into DMZ for home router
- create ddns service and add updater