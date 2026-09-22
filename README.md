# Square Era Database - Room 5: Anarchy Wilds

Persistent world modifications, player profiles, and session state for Square Era 3D Voxel Sandbox Room 5.

## Room Overview
- Room ID: 5
- Room Name: Anarchy Wilds
- Game Mode: SURVIVAL
- Description: High-Intensity PvP & TNT Blast Playground, crater mechanics, and wilderness warfare.
- Server Repository: [yasamarium/square-era-server-room5](https://github.com/yasamarium/square-era-server-room5)

## Schema & Files
- `data/world.json`: JSON map of persistent chunk modifications `[ ["x,y,z", blockId], ... ]`.
- `data/players.json`: Registered player profiles and session records.
- `data/chat.json`: Persistent in-room chat history.
- `data/sessions.json`: 5-hour runner cycle timestamps and synchronization checkpoints.

Zero external databases required. Backed 100% by GitHub Git persistence.
