# kstm Minecraft Server

Minecraft server and Configuration files using Spigot on docker-compose.

## Run

```bash
# start
sudo docker-compose up -d

# stop/start/restart minecraft server itself (not container)
sudo docker-compose exec main mc_stop    # stop
sudo docker-compose exec main mc_start   # start
sudo docker-compose exec main mc_restart # restart

# enter console
sudo docker-compose exec main java -jar /minecraft/spigot.jar nogui
```

