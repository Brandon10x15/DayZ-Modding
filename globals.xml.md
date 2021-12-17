# Table of Contents

 - [Home](https://github.com/Brandon10x15/DayZ-Modding/blob/main/README.md)
 - [db/globals.xml](https://github.com/Brandon10x15/DayZ-Modding/blob/main/globals.xml.md)

## db/globals.xml
0 for integer, 1 for float, 2 for string
|Variable|Type|Default|Unit|Description|
|--------|----|-------|----|-----------|
|AnimalMaxCount | Integer | 200 | - | Maximal limit of spawned animals (not ambient) across all zones in map |
|CleanupAvoidance|Integer|100|m|Distance from player required for item deletion|
|CleanupLifetimeDeadAnimal|Integer|1200|sec|Default lifetime for dead animals|
|CleanupLifetimeDeadInfected|Integer|330|sec|Default lifetime for dead infected
|CleanupLifetimeDeadPlayer|Integer|3600|sec|Default lifetime for dead player|
|CleanupLifetimeDefault|Integer|45|sec|Default lifetime for entities with no specific economy setup, but damage >= 1.0 (ie. dead)|
|CleanupLifetimeLimit|Integer|50|-|How many items can be deleted at once during standard cleanup|
|CleanupLifetimeRuined|Integer|330|sec|Default lifetime for ruined loot|
|FlagRefreshFrequency|Integer|432000|sec|Items lifetime will be refreshed with this frequency.|
|FlagRefreshMaxDuration|Integer|3456000|sec|How long the flag will be refreshing items.|
|FoodDecay|Integer|1|-|Allow decay on food (requires WorldWetTempUpdate set to 1).|
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
|WorldWetTempUpdate|Integer|1|-|Allow update of wetness and temperature values on all items in the world.|
|ZombieMaxCount|Integer|1000|-|Maximal limit of spawned zombies across all zones in map|
|ZoneSpawnDist|Integer|300|m|Distance to invoke infected spawn in nearby zone (dynamic infected)|


Default xml setup:
```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<variables>
    <var name="AnimalMaxCount" type="0" value="200"/>
    <var name="CleanupAvoidance" type="0" value="100"/>
    <var name="CleanupLifetimeDeadAnimal" type="0" value="1200"/>
    <var name="CleanupLifetimeDeadInfected" type="0" value="330"/>
    <var name="CleanupLifetimeDeadPlayer" type="0" value="3600"/>
    <var name="CleanupLifetimeDefault" type="0" value="45"/>
    <var name="CleanupLifetimeLimit" type="0" value="50"/>
    <var name="CleanupLifetimeRuined" type="0" value="330"/>
    <var name="FlagRefreshFrequency" type="0" value="432000"/>
    <var name="FlagRefreshMaxDuration" type="0" value="3456000"/>
    <var name="FoodDecay" type="0" value="1"/>
    <var name="IdleModeCountdown" type="0" value="60"/>
    <var name="IdleModeStartup" type="0" value="1"/>
    <var name="InitialSpawn" type="0" value="100"/>
    <var name="LootProxyPlacement" type="0" value="1"/>
    <var name="RespawnAttempt" type="0" value="2"/>
    <var name="RespawnLimit" type="0" value="20"/>
    <var name="RespawnTypes" type="0" value="12"/>
    <var name="RestartSpawn" type="0" value="0"/>
    <var name="SpawnInitial" type="0" value="1200"/>
    <var name="TimeHopping" type="0" value="60"/>
    <var name="TimeLogin" type="0" value="15"/>
    <var name="TimeLogout" type="0" value="15"/>
    <var name="TimePenalty" type="0" value="20"/>
    <var name="WorldWetTempUpdate" type="0" value="1"/>
    <var name="ZombieMaxCount" type="0" value="1000"/>
    <var name="ZoneSpawnDist" type="0" value="300"/>
</variables>
```