# kstm Minecraft Server

Minecraft server and Configuration files using Spigot on docker-compose.

## Run

```bash
# start
docker-compose up -d

# stop/start/restart minecraft server itself (not container)
docker-compose exec main mc_stop    # stop
docker-compose exec main mc_start   # start
docker-compose exec main mc_restart # restart

# sending command to the server console
docker-compose exec main mc_send COMMAND
```

