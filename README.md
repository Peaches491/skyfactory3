## How to use

* `docker create volume --name world_data`
* `docker create --name direwolf20 --restart always -v minecraft_world:/minecraft/world -p 25565:25565 -e EULA=TRUE direwolf20_1_10`
