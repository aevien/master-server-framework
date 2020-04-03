## Updates Log

### Msf 2.3.0 - Attention! Remove previous Barebones folder and than reimport new.

- Added **ISpawnerController** interface
- **SpawnerController** class is rewritten and now is extendable.
- Made some changes to **SpawnerBehaviour** and added two fields
 - **usePublicIp** - will help use use public IP address for your rooms
 - **region** - now you can set region in inspector
- **MsfArgs**
 - Added **StartSpawner** that will help to start spawner automatically
 - Added **RoomRegion** that will help you to set your spawner region from cmd

### Msf 2.2.4 - Attention! Remove previous Barebones folder and than reimport new.

- **RoomServerBehaviour** can be started registered both with spawner and just as standalone application. Use **startRoomAsProcess** field to control this feature. For more info see its script.
- **ConnectionToMaster** is now **ConnectionHelper** that can be extended to your own connection helper class.
- For quick connection to master use **ClientToMasterConnector**
- **SpawnerController** added some changed. Removed some static methods.
- **SpawnerBehaviour**  added some changed.
- **RoomsModule, SpawnersModule**. Made some fixes and added log messages. To see whole process of room spawning.

### Msf 2.2.3
---
- BaseClientModule is now more extandable
- Started to create Spawner demo
- Fixed bug in RegisteredSpawner class
- Fixed bug in SpawnerController class
- Fixed bug in SpawnTask class
- Fixed bug in SpawnerBehaviour class
- Fixed bug in SpawnersModule class