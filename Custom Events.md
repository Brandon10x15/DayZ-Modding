# Table of Contents

 - [Home](./README.md)
 - [Nitrado /custom Folder](./Nitrado%20custom%20Folder.md)
 - [Object Spawning](./Spawning%20Objects.md)
 - [Custom Events](./Custom%20Events.md)

## Custom Events
Lets add some custom events to our map.
  
Create a new file named `events_Custom.xml` in your `/custom` folder.

Open it in Notepad++ and add the following contents:  
```xml
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<events>
	<event name="VehicleTruck_Custom">
		<nominal>1</nominal>
		<min>1</min>
		<max>10</max>
		<lifetime>300</lifetime>
		<restock>0</restock>
		<saferadius>10</saferadius>
		<distanceradius>3</distanceradius>
		<cleanupradius>250</cleanupradius>
		<flags deletable="0" init_random="0" remove_damaged="1"/>
		<position>fixed</position>
		<limit>mixed</limit>
		<active>1</active>
		<children>
			<child lootmax="0" lootmin="0" max="10" min="10" type="Truck_01_Covered"/>
		</children>
	</event>
	<event name="ItemBuildingSupplies">
		<nominal>80</nominal>
		<min>80</min>
		<max>80</max>
		<lifetime>22000</lifetime>
		<restock>0</restock>
		<saferadius>0</saferadius>
		<distanceradius>0</distanceradius>
		<cleanupradius>0</cleanupradius>
		<flags deletable="1" init_random="0" remove_damaged="0"/>
		<position>fixed</position>
		<limit>child</limit>
		<active>1</active>
		<children>
			<child lootmax="0" lootmin="0" max="10" min="0" type="MetalPlate"/>
			<child lootmax="0" lootmin="0" max="20" min="0" type="WoodenPlank"/>
			<child lootmax="0" lootmin="0" max="50" min="0" type="WoodenLog"/>
		</children>
	</event>
</events>
```