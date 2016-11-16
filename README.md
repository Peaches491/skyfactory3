## How to use

```
docker volume create --name minecraft_world
docker create --name direwolf20 \
              --restart always \
              -v minecraft_world:/minecraft/world \
              -p 25565:25565 \
              -e EULA=TRUE \
              rootphish/direwolf20_1_10
```
