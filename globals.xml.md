# Table of Contents

 - [Home](https://github.com/Brandon10x15/DayZ-Modding/blob/main/README.md)
 - 

## db/globals.xml
0 for integer, 1 for float, 2 for string

|Variable| Type | Default | Unit | Description |
|-|-|-|-|-|-| 
|AnimalMaxCount|Integer|200|-|Maximal limit of spawned animals (not ambient) across all zones in map|
|CleanupAvoidance|Integer|100|m|Distance from player required for item deletion|
|CleanupLifetimeDeadAnimal|Integer|1200|sec|Default lifetime for dead animals|
|CleanupLifetimeDeadInfected|Integer|330|sec|Default lifetime for dead infected
|CleanupLifetimeDeadPlayer|Integer|3600|sec|Default lifetime for dead player|
|CleanupLifetimeDefault|Integer|45|sec|Default lifetime for entities with no specific economy setup, but damage >= 1.0 (ie. dead)|
|CleanupLifetimeLimit|Integer|50|-|How many items can be deleted at once during standard cleanup|
|CleanupLifetimeRuined|Integer|330|sec|Default lifetime for ruined loot|
|FlagRefreshFrequency|Integer|432000|sec|Items lifetime will be refreshed with this frequency.|
|FlagRefreshMaxDuration|Integer|3456000|sec|How long the flag will be refreshing items.|
|IdleModeCountdown|Integer|60|sec|Activate economy idle mode on empty server after given time|
|IdleModeStartup|Integer|1|-|0 to disable idle mode on server startup (will still switch on later if IdleModeCountdown is not 0)|
|InitialSpawn|Integer|100|%|How much loot will be spawned on server initial start (without storage).|
|LootProxyPlacement|Integer|1|-|Allow dispatch containers to receive the loot.|
|RespawnAttempt|Integer|2|-|How many attempts are performed during single item respawn|
|RespawnLimit|Integer|20|-|How many items of one type can be spawned at once|
|RespawnTypes|Integer|12|-|How many different types can be respawned at once|
|RestartSpawn|Integer|0|%|How much loot should be respawned during restart to nomimal|
|SpawnInitial|Integer|1200|-|How many initial test are allowed for item spawn|
|TimeHopping|Integer|60|sec|Penalty time for server hoppers|
|TimeLogin|Integer|15|sec|Default login time|
|TimeLogout|Integer|15|sec|Default logout time|
|TimePenalty|Integer|20|sec|Penalty time for player that is still in play session|
|ZombieMaxCount|Integer|1000|-|Maximal limit of spawned zombies across all zones in map|
|ZoneSpawnDist|Integer|300|m|Distance to invoke infected spawn in nearby zone (dynamic infected)|
|WorldWetTempUpdate|Integer|1|-|Allow update of wetness and temperature values on all items in the world.|
|FoodDecay|Integer|1|-|Allow decay on food (requires WorldWetTempUpdate set to 1).|

