## How to use

```
docker volume create --name minecraft_world
docker create --name skyfactory25 \
              --restart always \
              -v minecraft_world:/minecraft/world \
              -p 25565:25565 \
              -e EULA=TRUE \
              rootphish/skyfactory25
```
