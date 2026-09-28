# simple-shooter-game
A multiplayer-only FPS game for the [Luanti game engine](https://luanti.org). Currently very WIP.

Creating worlds is currently broken on a server, so if you wish to host a dedicated server, create a singlenode world on the client and transfer it to the server.

To play the game:

- `/maps` - List available maps (`forest` is a well tested and well loved map)
- `/start <map name>` - Start a match on `<map name>`
- `/stop` - Stop a match

Once you start a match with `/start`, you are placed on top of the map in a large glass room. During this time, you can change your class (different classes have different weapons) in the inventory formspec. Once the match start timer ends, you will be teleported a few nodes down through the barrier and the match begins.

Last player standing wins.
